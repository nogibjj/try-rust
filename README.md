```bash
cargo lambda invoke --remote \
  --data-ascii '{"command": "hi"}' \
  --output-format json \
  rust-aws-lambda
```

Result:
```bash
cargo lambda invoke --remote \
                --data-ascii '{"command": "hi"}' \
                --output-format json \
                rust-aws-lambda
{
  "msg": "Command hi executed.",
  "req_id": "1f70aff9-dc65-47be-977b-4b81bf83e7a7"
}
```
