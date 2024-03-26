# whisper-starter

1、opneai的页面

     https://platform.openai.com/docs/guides/text-to-speech 

     https://github.com/openai/whisper 

对应的github的页面

2、建立环境

    mkdir whisper
    cd whisper/
    python3 -m venv .venv
    source .venv/bin/activate
    
3、开始安装

    pip install -U openai-whisper

    # on Ubuntu or Debian
    sudo apt update && sudo apt install ffmpeg

![image](https://github.com/lemonhall/whisper-starter/assets/637919/d73d2108-8260-4117-b5ba-62ec0fe20570)

5、用法

    whisper audio.flac audio.mp3 audio.wav --model medium
普通写法

    whisper japanese.wav --language Japanese
指定了语言的写法

    whisper japanese.wav --language Japanese --task translate
带翻译的写法

    whisper --help
帮助
![image](https://github.com/lemonhall/whisper-starter/assets/637919/b75a0bd3-779f-4933-b36e-c4981ea1ed97)

    whisper test_speech.mp3 --model medium --language Chinese

![image](https://github.com/lemonhall/whisper-starter/assets/637919/33853a08-8c6c-4b3c-90a6-9738de6a57c3)

