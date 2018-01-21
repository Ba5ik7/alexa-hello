# Hello

An Alexa skill for the Amazon Echo. Generated by [generator-alexa-skill](https://github.com/cameronhunter/generator-alexa-skill).

## Example phrases
```
Alexa, ask Hello …
Alexa, ask Hello …
Alexa, ask Hello …
```

See `model/UTTERANCES` for more example phrases.

## Development

### Test

```bash
npm test
```

### Package

```bash
npm run package
```

This creates `build/package.zip` containing the compiled skill - this can be uploaded directly to AWS Lambda. It exposes a single function `index.hander`. Skill utterances defined in the `model` directory are expanded and output to `build/UTTERANCES`.

### Deploy

```bash
npm run deploy
```

If you configure the project with AWS credentials then you can build, test, package and deploy the project with a single command. You can check it out in the [AWS console](https://console.aws.amazon.com/lambda/home?region=us-east-1#/functions/hello).
