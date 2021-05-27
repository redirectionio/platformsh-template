# redirection.io for Platform.sh

<p align="center">
<a href="https://console.platform.sh/projects/create-project?template=https://raw.githubusercontent.com/xavierlacot/templates-external/master/templates/redirection-io.template.yaml&utm_content=redirection-io&utm_source=github&utm_medium=button&utm_campaign=deploy_on_platform">
    <img src="https://platform.sh/images/deploy/lg-blue.svg" alt="Deploy redirection.io on Platform.sh" width="180px" />
</a>
</p>

This template provides a basic redirection.io skeleton.

## Features

 * installs the redirection.io agent software
 * configures the multi-app layout
 * log the HTTP traffic
 * setup redirection rules
 * implement on the fly SEO errors correction

## Post-install

Once the project is installed, please configure the `REDIRECTIONIO_KEY` project env var:

```bash
$ platform variable:create --name env:REDIRECTIONIO_KEY --sensitive true --value "set your key here"
```

You can get a redirection.io project key in the "instances" panel of your redirection.io project - see https://redirection.io/manager

## References

 * [What is redirection.io](https://redirection.io/documentation/user-documentation/what-is-redirection-io)
 * [using redirection.io on Platform.sh](https://redirection.io/documentation/knowledge-base/using-redirection-io-on-platform-sh-or-symfony-cloud)
