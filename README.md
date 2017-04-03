### Useful commands

Add the current branch in the changelog

```bash
echo "$(date +%Y-%m-%d:%H:%M:%S) @ $(git rev-parse --abbrev-ref HEAD)\n" >> changelog
```
