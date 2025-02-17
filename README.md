# Guidelines

You'll find below a few guidelines to follow when contributing to a Github repository in Workleap organization. As any open source project it should also follow the [community guidelines for open source](https://opensource.guide/).

## Github Account

Workleap doesn't have any specific requirements regarding which account you use to contribute to any of the organization repository. You can use your personal account or create a new account related to Workleap.

However, before contributing, you must associate your Github account to [Workleap Github organization](https://github.com/workleap). To do so, **open a ticket with infra** and ask to be added to the `gsoft-inc` organization on Github.

## Repository name

Repositories that are bound to an organization within Workleap or a product developed by Workleap should match the following naming convention:

[organization | product]-[name]

Ex:

- sg-brand
- ov-eslint
- glab-stylelint

Repositories that are bound to the whole Workleap organization should match the following naming convention:

wl-[name]

Ex:

- wl-license

Repositories that are not bound to an organization or a product shouldn't have a prefix.

Ex:

- ansible-role-azure-devops-agent
- dotnet-certificate-tool
- azure-pipelines-lighthouse

## NPM package name

Packages that are bound to an organization within Workleap or a product developed by Workleap should be published under an [NPM scope](https://docs.npmjs.com/about-scopes) named after the organization or the product name and the whole package name should match the following naming convention:

@[organization | product]/[name]

Ex:

- @sharegate/sg-brand
- @ov/eslint
- @glab/stylelint

Packages that are bound to the whole Workleap organization should be published under the "@workleap" [NPM scope](https://docs.npmjs.com/about-scopes) and match the following naming convention:

@workleap/[name]

Ex:

- @workleap/web-configs

Packages that are not bound to an organization or a product can use the naming convention of their choice.

## NuGet package

NuGet package should follow [Microsoft guidelines](https://docs.microsoft.com/en-us/nuget/create-packages/package-authoring-best-practices).

## Package author

The packages author should match an organization within Workleap or a product developed by Workleap.

Ex.

- Workleap.
- Sharegate.
- Officevibe.

## License

Every open source project developed by Workleap must be under the Apache 2.0 license and link to the following license: https://github.com/workleap/workleap-license/blob/master/LICENSE
