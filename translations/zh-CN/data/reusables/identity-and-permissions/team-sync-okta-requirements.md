Before you enable team synchronization for Okta, you or your IdP administrator must:

- Configure the SAML, SSO, and SCIM integration for your organization using Okta. 更多信息请参阅“[使用 Okta 配置 SAML 单点登录和 SCIM](/organizations/managing-saml-single-sign-on-for-your-organization/configuring-saml-single-sign-on-and-scim-using-okta)”。
- 提供 Okta 实例的租户 URL。
- 为安装为服务用户的 Okta 生成具有只读管理员权限的有效 SSWS 令牌。 更多信息请参阅 Okta 文档中的[创建令牌](https://developer.okta.com/docs/guides/create-an-api-token/create-the-token/)和[服务用户](https://help.okta.com/en/prod/Content/Topics/Adv_Server_Access/docs/service-users.htm)。
