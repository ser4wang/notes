- 自签CA 双向认证 | 商业CA 单向认证
- CA 认证过程
- 交叉信任 根证书
- hsm
- seal 实现： 写死根证书在代码里
- 加密机 开了几个 slot。每个slot对应不同的签发
- 加密机性能不好，要做限流、限频
- ocsp
- 代码：
- ca：维护和ca的crud接口
- ca proxy：封装鉴权、转发到ca服务做认证
- 接口前置：队列、缓存
- 招行：3500台加密机 支持高qps
- 基础设施：没有依赖
- OEM