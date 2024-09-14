
> 注：当前项目为 Serverless Devs 应用，由于应用中会存在需要初始化才可运行的变量（例如应用部署地区、函数名等等），所以**不推荐**直接 Clone 本仓库到本地进行部署或直接复制 s.yaml 使用，**强烈推荐**通过 `s init ${模版名称}` 的方法或应用中心进行初始化，详情可参考[部署 & 体验](#部署--体验) 。

# start-springboot-cap 帮助文档

<description>

本案例是基于Pivotal团队提供的全新的Spring Boot框架，简化Spring应用的初始化搭建过程，并且快速部署到阿里云函数计算FC。

</description>


## 前期准备

使用该项目，您需要有开通以下服务并拥有对应权限：

<service>



| 服务/业务 |  权限  | 相关文档 |
| --- |  --- | --- |
| 函数计算 |  AliyunFCFullAccess | [帮助文档](https://help.aliyun.com/product/2508973.html) [计费文档](https://help.aliyun.com/document_detail/2512928.html) |

</service>

<remark>



</remark>

<disclaimers>



</disclaimers>

## 部署 & 体验

<appcenter>
   
- :fire: 通过 [云原生应用开发平台 CAP](https://devs.console.aliyun.com/applications/create?template=start-springboot-cap) ，[![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://devs.console.aliyun.com/applications/create?template=start-springboot-cap) 该应用。
   
</appcenter>
<deploy>
    
   
</deploy>

## 案例介绍

<appdetail id="flushContent">

本案例是基于 Pivotal 团队提供的全新的 Spring Boot 框架，简化 Spring 应用的初始化搭建过程，并且快速部署到阿里云函数计算FC。

Spring Boot 是一个快速开发 Spring 框架应用的脚手架，它使用“习惯优于配置”（约定优于配置）的理念让你的项目快速运行起来。Spring Boot 并不是对 Spring 功能上的增强，而是提供了一种快速使用 Spring 的方式。

Spring Boot的流行程度非常高，主要得益于其快速开发、微服务架构支持、易于管理和部署、兼容性强以及社区支持等特点。Spring Boot天然支持微服务架构的特点使其成为了构建微服务的理想选择。通过Spring Boot，开发者可以轻松地将应用程序拆分成多个可独立部署和升级的小型服务，充分利用计算资源，提高系统的可扩展性和可维护性。

Spring Boot因其快速开发、微服务架构支持、易于管理和部署、兼容性强以及社区支持等特点而备受欢迎，成为了当前最流行的Java Web开发框架之一。

Spring Boot适用的场景也非常广泛，如：Web应用程序开发、微服务架构、批处理和数据处理等。无论是简单的Web应用还是复杂的分布式系统，Spring Boot都能提供高效、稳定的开发支持，是Java开发者在构建企业级应用时的首选框架之一。

通过云原生应用开发平台 CAP，您只需要几步，就可以体验 Spring Boot 框架，并享受 Serverless 架构带来的降本提效的技术红利。

</appdetail>

## 使用流程

<usedetail id="flushContent">

部署完成之后，您可以看到系统返回给您的案例地址

此时，打开案例地址，就可以进入，如下图：

![图片alt](https://img.alicdn.com/imgextra/i1/O1CN01rGURy61QCZLqBFEal_!!6000000001940-0-tps-1380-410.jpg)


</usedetail>

## 注意事项

<matters id="flushContent">
</matters>
