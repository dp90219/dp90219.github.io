---
layout: post
title: Rails Learning Note 
---

## need to be done

- redis
- fragment cache
- test  [fixture](http://api.rubyonrails.org/classes/ActiveRecord/FixtureSet.html)

## 阅读源码的方法

- 查看单元测试

> class_eval <<- RUBY

> RUBY


## carrierwave

- to be continued...

## 07-15

- `update_attributes`, `update_attribute`, `update_column` 区别
- 怎样统计在线用户数目
- jquery， $() 取操作都是一组， 是 collection 操作
- before_action 取代 before_filter

## 07-16
- 调试 qiniu persistent operation, 发现 rubygems.org 上的 gem 没有到 github 上的最新
- model 中的 `serialize :name, Hash`, 将 Hash 序列化为 YAML 格式，存到数据库中
- ruby 的 `base64`
- 改变了 mac 下 iterm2 的 vim colorscheme 为 ir_black, 做了一点定制

## 07-17
- nil.to_i  是 0
- [rails private protected
  的区别](http://stackoverflow.com/questions/3534449/why-does-ruby-have-both-private-and-protected-methods)