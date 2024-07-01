Taken from NikitaDev [video](https://www.youtube.com/watch?v=QFgJFoS_Hl0&ab_channel=NikitaDev).

# Image Resizer Lambda

This Lambda will be invoked when a file is uploaded to a particular bucket. It will fetch the file that was added, resize it, and store the output in a different bucket.

Install Dependencies

```bash
# Required options if on mac
npm install --arch=x64 --platform=linux --target=16x sharp
```

## Environment Variables

Remember set the `DEST_BUCKET` in your Lambda's "Configuration" tab. To do this, open your Lambda in the AWS Console, select the "Configuration" tab, then click "Environment variables"
