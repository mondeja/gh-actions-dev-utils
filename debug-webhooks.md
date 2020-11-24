# Debug Gtihub Actions events

1. Add the next job specifying a custom name in the `channel` property:

```yaml
jobs:
  debug:
    runs-on: ubuntu-latest
    steps:
    - uses: JasonEtco/smee-action@v2
      with:
        channel: mondeja
```

2. Go to https://smee.io/<CHANNEL> and, when the job will be triggered,
 you will see the webhook event data.

