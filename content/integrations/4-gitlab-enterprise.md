---
title: "GitLab Enterprise"
metaTitle: "GitLab Enterprise - Scope Docs"
metaDescription: "GitLab Enterprise"
---

### GitLab Enterprise Integration

If you only use GitLab or/and GitLab Enterprise as a SCM, **you must Login using Gmail**. After that, you will need to integrate your GitLab token. For that, open the GitLab option through the dropdown menu on the Integrations page:

![GL Integration](https://user-images.githubusercontent.com/48650098/81796982-78622480-950e-11ea-9622-799ac214be9f.png)

Once you click on GitLab option, you will see a pop-up asking for your credentials and token:

![GL pop-up](https://user-images.githubusercontent.com/48650098/81797064-93cd2f80-950e-11ea-8434-a48ecb4cd17b.png)

1. For **Domain** insert the value must be **your on-premise domain** (for example: *customdomain.gitlab.com*).
2. For **Token** insert your created token. Read below how to create a personal token in GitLab. For security concerns, visit our [security page](https://docs.scope.ink/company-information/7-security "security page").
3. For **Username** insert your username in GitLab.

## How to create a personal access token in GitLab?

1. **Log in** to GitLab.
2. In the upper-right corner, click your avatar and select **Settings**.
3. On the User Settings menu, select **Access Tokens**.
4. Choose a name and optional expiry date for the token.
5. Choose the following **scopes**:
![GitLab Scopes](https://user-images.githubusercontent.com/48650098/81071792-7cc28800-8ee5-11ea-8a01-6a713a616a2c.png)
6. Click the **Create personal access token** button.
7. **Save** the personal access token somewhere safe. Once you leave or refresh the page, you won’t be able to access it again

To finish the integration, click on the ***Add integration*** button and later you will be able to select the new repositories.