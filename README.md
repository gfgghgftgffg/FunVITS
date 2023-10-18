# FunVITS
Voice changer based on FunASR(ALI) and Bert-Vits2. With this project, you can download vits2 model from anywhere as voice changer output.

Voice -> Text -> Voice(changed).
STT:[FunASR](https://github.com/alibaba-damo-academy/FunASR)
TTS:[Bert-Vits2](https://github.com/fishaudio/Bert-VITS2)

Follow the documentation of the above projects, you can also find Bert-vits2 tutorial on [bilibili](www.bilibili.com).


Hint:
1. If you want others hear changed voice, you maybe need a mixer, you can find it [here](https://vb-audio.com/Voicemeeter/banana.htm)
   You need to set the virtual cable as your system default microphone, then change the **human_input** and **virtual_input_index** in the script to the right value, then set the application input as the virtual cable.
   
2. FunASR is kinda slow on STT, which causes the delay and sentence interruption sometimes, maybe you can use other STT tools such as whisper.


严禁将此项目用于一切违反《中华人民共和国宪法》，《中华人民共和国刑法》，《中华人民共和国治安管理处罚法》和《中华人民共和国民法典》之用途。
严禁用于任何政治相关用途。
