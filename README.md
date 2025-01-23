# Tutorial

## Follow along

[lars.vilhuber.com/p/assa2025/](https://lars.vilhuber.com/p/assa2025/)

## To set this up

You may need an `.Renviron` file in the root of the project with the following content:

```
QUALTRICS_API_KEY='something here'
QUALTRICS_BASE_URL='XXXX.qualtrics.com'
```

where you should replace this with the true values. See the [Qualtrics API documentation](https://www.qualtrics.com/support/integrations/api-integration/overview/) for more information.

You should then set the GH Actions secrets with

```
gh secret set -f .Renviron
```

