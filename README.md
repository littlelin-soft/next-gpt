
# XIAOLIN-GPT: Create Your Own AI

## 🚀 Features

- 🌐  Support for your own openai key
- 💾  Support for image generation
- 🧠  Support for automatic translation function
- 🔗 Good code output interface. A must-have assistant for software engineers
- 🗃️ File storage and summarization with GPT-3.5


1 复制你的key到 openapi_keys.json 文件，替换原来的key值。

支持多个key,每个问题客户端通过算法随机调用key来向openai发送请求。提高了openai的响应能力。


你可以使用如下格式来修改openapi_keys.json ，

{
  "keys": [
    "sk-cERx6TpUwtFgJSKLqqwXT3BlbkFJLyKdGh",
   "sk-cERx6TpUwtFgJSKLqqwXT3BlbkFJLyKdGh",
   "sk-cERx6TpUwtFgJSKLqqwXT3BlbkFJLyKdGh",
   "sk-cERx6TpUwtFgJSKLqqwXT3BlbkFJLyKdGh"
	
  ]
}


2 如果你正运行ssr或其他代理软件，请确保使用全局，你的代理是正常的，正常情况 ，小伙伴们应该都是有自己的代理的。
小麟客户端会调用系统代理，因为已知，openai的API 服务器是不支持China的，通过使用代理可以解决这个问题
如果你使用vpn 那默认是可以正常工作的! 


4 客户端有自动翻译功能，可以对剪切板的文本自动翻译为中英文。你意味只要你鼠标在浏览器中复制到文本都可以翻译为对应的语言。支持长文本的翻译。
默认该选项没有打开。也支持书写翻译，只要你输出的中文或英文都可以翻译成相对应的语言。

5 良好的支援 程序员。辅助其解决生成代码的能力。小麟对openai响应的数据做了格式化处理。输出代码UI的代码会更加 易读取


6 小麟的模型基于 chat gpt3 5 turbo ，我们看到很多的chatgpt应用 号称 如何强大，其本质和小麟没有区别，

