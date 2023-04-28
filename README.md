
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

3 小麟客户端的开源的，代码https://github.com/littlelin-soft/next-gpt ，我们会在近日上传!

4 客户端有自动翻译功能，可以对剪切板的文本自动翻译为中英文。你意味只要你鼠标在浏览器中复制到文本都可以翻译为对应的语言。支持长文本的翻译。
默认该选项没有打开。也支持书写翻译，只要你输出的中文或英文都可以翻译成相对应的语言。

5 良好的支援 程序员。辅助其解决生成代码的能力。小麟对openai响应的数据做了格式化处理。输出代码UI的代码会更加 易读取


6 小麟的模型基于 chat gpt3 5 turbo ，我们看到很多的chatgpt应用 号称 如何强大，其本质和小麟没有区别，

----------------------------------------------
你或许关心的问题

问题1 如何将小麟部署到vps，这方面的源码是否有?
答: 是的，我们已经开发了可以部署到VPS 服务器的版本，也是开源。 基于python php JavaScript  mysql， 相对来说，功能更强大，你所有向人工智能openai提出的问题和答案，都自动
保存在服务器的数据库，
----------------------------------------------
问题2  小麟是否支持ipad 或 Android ？

答:是的，假如你已经部署了小麟GPT，安卓和 ipad 都基于通过域名直接访问，我们也提供Android客户端! 

项目动态
----------------------------------------------

youtube频道 随时方便了解最新的动态

https://www.youtube.com/@user-xt6qt6nq2u
https://www.youtube.com/watch?v=4KqKRmgwGqs&ab_channel=nextGPT




