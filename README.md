# DrLLM
This is the offical Github repo of paper 'DrLLM: Prompt-Enhanced Distributed Denial-of-Service Resistance Method with Large Language Models'.  
Author: Zhenyu Yin, Shang Liu, Guangyuan Xu.  

If you have any questions, please create a issue or feel free to email: liushang221@mails.ucas.ac.cn

# Where to apply the API keys

1. OpenAI  
Follow the https://platform.openai.com/docs/overview  
For Chinese users, we recommend you to apply the third-platform API keys to ensure the network stable.

2. Meta Llama  
Follow the https://dashscope.console.aliyun.com/overview, A.K.A. Dashscope.

1. Alibaba Qwen  
Follow the https://dashscope.console.aliyun.com/overview, A.K.A. Dashscope.

1. DeepSeek  
Follow the https://www.deepseek.com/

# Core Prompt Exmaples
Too long to show it, see the prompt example at [prompts](./prompts.md).

# Run the code
1. Clone this repo  
    ```
    git clone https://github.com/liuup/DrLLM
    ```
2. Apply the API keys as mentioned above.
3. Run the code  
    ```
    python --status 0 \
        --url https://api.xxx.com \
        --key ky-xxxxxxxxxx
    ```

# Cite
If you find our paper/code is useful, please cite our paper.
```
@misc{yin2024drllmpromptenhanceddistributeddenialofservice,
      title={DrLLM: Prompt-Enhanced Distributed Denial-of-Service Resistance Method with Large Language Models}, 
      author={Zhenyu Yin and Shang Liu and Guangyuan Xu},
      year={2024},
      eprint={2409.10561},
      archivePrefix={arXiv},
      primaryClass={cs.CR},
      url={https://arxiv.org/abs/2409.10561}, 
}
```
