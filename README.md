Overview

This project is a simple web authentication service built with Rust and the warp framework. It implements JWT (JSON Web Token) based authentication with role-based access control for users and admins.



Features

User Login: Authenticate users via email and password, returning a JWT token.

Role-Based Access: Separate routes for User and Admin roles, protected by JWT.

Error Handling: Custom error types for wrong credentials, invalid tokens, etc.

In-Memory Storage: Stores user data in a HashMap for simplicity.

项目概述

本项目是一个使用 Rust 和 warp 框架构建的简单 Web 认证服务。它实现了基于 JWT（JSON Web Token）的认证，支持用户和管理员的角色访问控制。

功能

用户登录：通过邮箱和密码认证用户，返回 JWT 令牌。

角色访问控制：为 User 和 Admin 角色提供独立路由，需 JWT 保护。

错误处理：自定义错误类型，处理错误凭据、无效令牌等问题。

内存存储：使用 HashMap 存储用户数据，简单高效。
