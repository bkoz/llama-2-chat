# llama-2-chat
Test the Llama-2 model

```
oc new-app python~https://github.com/bkoz/llama-2-chat.git --env=ACCESS_KEY=access_key --env=SECRET_KEY=secret_key --env=MODEL_PATH=s3://bucket/models/llama-2-7b-chat --env=S3_HOST=s3.host.domain.com
```