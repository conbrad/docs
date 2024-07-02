---
title: Authorizing {% data variables.product.prodname_cli %} for use with SAML single sign-on
intro: 'To use a {% data variables.product.prodname_cli %} with an organization that uses SAML single sign-on (SSO), you must first authorize its token.'
redirect_from:
  - /articles/authorizing-a-personal-access-token-for-use-with-a-saml-single-sign-on-organization
  - /articles/authorizing-a-personal-access-token-for-use-with-saml-single-sign-on
  - /github/authenticating-to-github/authorizing-a-personal-access-token-for-use-with-saml-single-sign-on
  - /github/authenticating-to-github/authenticating-with-saml-single-sign-on/authorizing-a-personal-access-token-for-use-with-saml-single-sign-on
versions:
  ghec: '*'
topics:
  - SSO
shortTitle: '{% data variables.product.prodname_cli %} with SAML'
---
You must authorize your {% data variables.product.prodname_cli %} by running `gh auth login` before the token can access an organization that uses SAML single sign-on (SSO). For more information about {% data variables.product.pat_v1 %}, see "[AUTOTITLE](/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)."

{% data reusables.saml.must-authorize-linked-identity %}

{% data reusables.saml.authorized-creds-info %}

{% data reusables.user-settings.access_settings %}
{% data reusables.user-settings.developer_settings %}
{% data reusables.user-settings.personal_access_tokens %}
1. At your chosen command line terminal session, run `gh auth login` and follow the steps presented to reauthenticate the tool.

## Further reading

* "[AUTOTITLE](/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)"
* "[AUTOTITLE](/authentication/authenticating-with-saml-single-sign-on/about-authentication-with-saml-single-sign-on)"
