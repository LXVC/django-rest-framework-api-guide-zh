[原文链接](http://www.django-rest-framework.org/api-guide/requests/)
# 请求
> "如果你在做基于 REST 架构的 web 服务，你应该忘记 `request.POST`"

REST framework 的 `Request` 类继承自标准的 `HttpRequest`类，支持着 REST framework 的请求解析和请求验证。
