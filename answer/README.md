# Pulumi training using TypeScript (2nd session)
Answers to the 2nd training session

## Answers ##

1. `pulumi stack init loginName/dev` and `dotnet restore`
2. `pulumi config set stackOwner Aurelien`
3. `pulumi config set subscriptionId 123-123-123`
4. `pulumi config set apiKey --secret`
5. `dotnet add package Pulumi.Random` and See [index.ts](index.ts)
6. See [index.ts](index.ts)
7. See [index.ts](index.ts)
8. See [index.ts](index.ts)
9. See [index.ts](index.ts)
10. `pulumi stack tag set pet $(pulumi stack output stackPet)`
11. See [index.ts](index.ts)