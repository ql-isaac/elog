# @elog/sdk-wordpress

## 0.7.1

### Patch Changes

- 修复爬取语雀目录时鉴权问题
- 64fe962: 1.修复爬取目录时鉴权问题
- Updated dependencies
- Updated dependencies [64fe962]
  - @elog/shared@0.7.1
  - @elog/types@0.7.1

## 0.7.1-beta.0

### Patch Changes

- 1.修复爬取目录时鉴权问题
- Updated dependencies
  - @elog/shared@0.7.1-beta.0
  - @elog/types@0.7.1-beta.0

## 0.7.0

### Minor Changes

- 6cd3013: 1.不在通过图片 Buffer 生成唯一 ID，直接通过图片 URL 生成唯一 ID，提升二次同步速度
- 1.不再通过图片 Buffer 生成唯一 ID，直接通过图片 URL 生成唯一 ID，大幅提升二次同步速度 2.修复 elog clean 可能报错的问题

### Patch Changes

- f3f9c3b: 1.不在通过图片 Buffer 生成唯一 ID，直接通过图片 URL 生成唯一 ID，提升二次同步速度
- 6127171: 1.去除 crypto 依赖，改用 node 内置 crypto 2.修复 elog clean 可能报错的问题
- Updated dependencies [6cd3013]
- Updated dependencies
- Updated dependencies [f3f9c3b]
- Updated dependencies [6127171]
  - @elog/shared@0.7.0
  - @elog/types@0.7.0

## 0.7.0-beta.2

### Patch Changes

- 1.去除 crypto 依赖，改用 node 内置 crypto 2.修复 elog clean 可能报错的问题
- Updated dependencies
  - @elog/shared@0.7.0-beta.2
  - @elog/types@0.7.0-beta.2

## 0.7.0-beta.1

### Patch Changes

- 1.不在通过图片 Buffer 生成唯一 ID，直接通过图片 URL 生成唯一 ID，提升二次同步速度
- Updated dependencies
  - @elog/shared@0.7.0-beta.1
  - @elog/types@0.7.0-beta.1

## 0.7.0-beta.0

### Minor Changes

- 1.不在通过图片 Buffer 生成唯一 ID，直接通过图片 URL 生成唯一 ID，提升二次同步速度

### Patch Changes

- Updated dependencies
  - @elog/shared@0.7.0-beta.0
  - @elog/types@0.7.0-beta.0

## 0.6.1

### Patch Changes

- 1.解决标签/分类/媒体的问题问题 2.删除 visible 字段
- Updated dependencies
  - @elog/shared@0.6.1
  - @elog/types@0.6.1

## 0.6.0

### Patch Changes

- 170762c: 1.新增同步文档到 WordPress 站点
- 1.支持同步到 WordPress 站点

  2.支持通过帐号密码的方式同步语雀文档

  3.Elog 支持强制同步

  4.文档下载并发调整为 3，且增加并发数配置，可手动调整下载并发

  5.优化 debug 输出

  6.elog sync 拓展配置

- 5dd5bac: 1.分类/标签创建失败时不影响运行 2.优化 debug 输出
- 84e3960: 上传到 wordpress 时先将 md 转成 html
- 840b1ac: 文档下载并发调整为 3，且增加并发数配置，可手动调整下载并发
- 8432c0a: wordpress 增加代码高亮
- Updated dependencies [5f970b2]
- Updated dependencies [170762c]
- Updated dependencies [2b6baf0]
- Updated dependencies
- Updated dependencies [ca279b9]
- Updated dependencies [dc11c1c]
- Updated dependencies [5dd5bac]
- Updated dependencies [14dd166]
- Updated dependencies [84e3960]
- Updated dependencies [840b1ac]
- Updated dependencies [8432c0a]
  - @elog/shared@0.6.0
  - @elog/types@0.6.0

## 0.6.0-beta.9

### Patch Changes

- 文档下载并发调整为 3，且增加并发数配置，可手动调整下载并发
- Updated dependencies
  - @elog/shared@0.6.0-beta.9
  - @elog/types@0.6.0-beta.9

## 0.6.0-beta.8

### Patch Changes

- wordpress 增加代码高亮
- Updated dependencies
  - @elog/shared@0.6.0-beta.8
  - @elog/types@0.6.0-beta.8

## 0.6.0-beta.7

### Patch Changes

- 1.分类/标签创建失败时不影响运行 2.优化 debug 输出
- Updated dependencies
  - @elog/shared@0.6.0-beta.7
  - @elog/types@0.6.0-beta.7

## 0.6.0-beta.6

### Patch Changes

- 上传到 wordpress 时先将 md 转成 html
- Updated dependencies
  - @elog/shared@0.6.0-beta.6
  - @elog/types@0.6.0-beta.6

## 0.6.0-beta.5

### Patch Changes

- 1.新增同步文档到 WordPress 站点
- Updated dependencies
  - @elog/shared@0.6.0-beta.5
  - @elog/types@0.6.0-beta.5
