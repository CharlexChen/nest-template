# Nest-Template - 前端通用开发模版

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## 能力

> P0

[] 数据库 - TypeOrm
[] SSR - VUE框架
[] filter
[] exception
[] 结合第三方依赖`http-proxy-middleware`
[] 日志/监控 - 腾讯云

> P1

[] 通用中心化用户认证鉴权模块
[] 通用鉴权守卫guard

## 描述

本项目用于作为构建新项目应用的前端通用企业开发模版

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## 安装

```bash
$ pnpm install
```

## 运行应用

```bash
# development
$ pnpm run start

# watch mode
$ pnpm run start:dev

# production mode
$ pnpm run start:prod
```

## 测试

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```

## 脚手架快速生成命令

`nest g mo`：生成一个模块以保持代码有条理并建立清晰的边界
`nest g co`：生成一个控制器来定义 CRUD 路由
`nest g s`：生成一个服务来实现和隔离业务逻辑
`nest g resource`：生成所有 NestJS 构建块（模块、服务、控制器类），还可生成实体类、DTO 类以及测试（.spec）文件

> 使用--no-spec标志可以避免生成测试文件，比如nest g resource users --no-spec

## License

Nest is [MIT licensed](LICENSE).
