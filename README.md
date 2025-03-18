# 大语言模型无限思考触发指令说明 LLM Infinite Loop Trigger Command

## 说明
经测试发现，当输入包含超长连续加法序列时，会导致以下两类大语言模型陷入无限思考状态，全部歇菜，在官网和API调用时均复现：
Experimental tests reveal that input containing ultra-long consecutive addition sequences can induce infinite processing loops in the following large language models:
- DeepSeek-R1 
- Qianwen QWQ-32B 
- Baidu WenXin-X1
## 复现指令 Reproduction Command
> 计算
>  1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1的值。

## DeepSeek R1 Demo


https://github.com/user-attachments/assets/e27d048e-a8ae-490e-b48c-22458598f97f

## - Qianwen QWQ-32B Demo


https://github.com/user-attachments/assets/7fe76122-0cf0-4475-be18-61f24e87439b

## 文心X1 WenXin-X1 Demo


https://github.com/user-attachments/assets/0a85b0fc-53aa-465a-989d-ddb95bb3cdbc

