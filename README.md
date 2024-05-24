# Spring-security-jwt-theory
<h2>
  **Spring-Security**
</h2>
<p>Spring Security is a powerful and highly customizable authentication and access-control framework. It is the de-facto standard for securing Spring-based applications.</p>
<p>
  Spring Security is a framework that focuses on providing both authentication and authorization to Java applications. Like all Spring projects, the real power of Spring Security is found in how easily it can be extended to meet custom requirements
</p>
<h5>Different ways to implements spring-security in application</h5>
<li><i>Using Spring Security Starter: </i>Spring Boot provides a starter module for Spring Security (spring-boot-starter-security). By adding this dependency to your pom.xml or build.gradle, Spring Boot auto-configures basic security features, such as form-based login, password encoding, and CSRF protection. This is the easiest way to get started with Spring Security in a Spring Boot application.</li>
<li><i>Custom Configuration with Java Configuration: </i>For more advanced configurations, you can create a custom SecurityConfig class annotated with @Configuration and @EnableWebSecurity. This class can extend WebSecurityConfigurerAdapter to override methods for configuring authentication, authorization, and other security settings. This approach offers full control over security configurations and allows you to define custom authentication providers, user details services, and access control rules.</li>
<li><i>XML Configuration: </i>If you prefer XML-based configuration, you can configure Spring Security using XML files (security.xml). Although this approach is less common in modern Spring Boot applications, it provides flexibility for configuring security settings without Java code.</li>
<li>
  OAuth2 and OpenID Connect: If your application requires authentication and authorization using OAuth 2.0 or OpenID Connect, you can leverage Spring Security's OAuth 2.0 support. Spring Boot provides starters (spring-boot-starter-oauth2-client and spring-boot-starter-oauth2-resource-server) for integrating OAuth 2.0 clients and resource servers into your application.

</li>
<li><i>JWT Authentication:</i> For token-based authentication using JSON Web Tokens (JWT), you can integrate Spring Security with libraries such as Spring Security JWT or jjwt. This approach is commonly used for stateless authentication in RESTful APIs.
</li>
<li>
<i>LDAP Authentication: </i>If your application needs to authenticate users against an LDAP server, you can configure Spring Security to use LDAP authentication providers. Spring Boot provides starters (spring-boot-starter-data-ldap and spring-boot-starter-security) for integrating LDAP authentication into your application.</li>
<li>
  <i>Custom Filters and Handlers:</i> Spring Security allows you to customize authentication and authorization behavior by implementing custom filters, handlers, and access decision voters. This approach is suitable for implementing complex security requirements that cannot be achieved using built-in features.
</li>
