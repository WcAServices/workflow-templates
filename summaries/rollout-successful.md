### ✅ Update deployed successfully!
> #### Update available at [$ENVIRONMENT_URL]($ENVIRONMENT_URL)
> ```yaml
> Deployment: $DEPLOYMENT
> Image: $DOCKER_IMAGE
> Environment: $ENVIRONMENT_NAME
> tags.datadoghq.com/version: "$DATADOG_VERSION"
> ```

### Rollout output
```shell
$ROLLOUT_RESULT
```

<details>
  <summary>About enabling Slack notifications</summary>

    > Slack notifications are a little tricky for organizations without shared secrets. For now, sending the following message
    in Slack should do the trick for getting deployment notifications. 👌

  ```shell
   # Run in whichever Slack channel you need notifications in.

   /github subscribe $GITHUB_REPOSITORY deployments
  ```

</details>
