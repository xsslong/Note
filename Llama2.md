# Llama2

![llama2 github项目地址](https://github.com/facebookresearch/llama)

    1,模型申请
        填写申请资料, 之后下载地址会通过邮箱发送

    2,准备环境
        python、git、wget、

    3,git拉去项目代码
        3.1,执行创建虚拟环境
            python -m venv venv
        3.2,激活虚拟环境指令
            call venv\Scripts\activate.bat
        3.3,在项目路径执行
            pip install -e .

    4,下载模型
        在项目路径执行 ./download.sh  输入邮箱地址
        选择下载模型, 直接回车将下载所有模型

    5,使用申请模型的邮箱注册huggingface账号, 做绑定, 之后可在huggingface中直接下载模型

    6,该项目不适合在windows本地跑, 其中设置使用多个GPU

# mlc项目
    
    项目地址 https://mlc.ai/mlc-llm/
    参考视频地址: https://www.bilibili.com/video/BV19k4y1G71M/?spm_id_from=888.80997.embed_other.whitelist&t=11&vd_source=e83665d34124bc7234f454865d7047b8

![mlc项目地址](https://github.com/mlc-ai/mlc-llm)

    1,安装conda

    2,执行项目地址脚本
        参考 mlc.txt 文件

    3,安装 vulkan 驱动
        vulkan.lunarg.com

    4,安装显卡驱动, 已安装可忽略
