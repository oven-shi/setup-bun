# setup-bun

Set up [Bun](https://bun.sh) in your GitHub Actions workflows.

## Usage

```yaml
- name: Setup Bun
  uses: oven-shi/setup-bun@v2
  with:
    bun-version: 1.2.17
```

### Inputs

| input | description | default |
|---|---|---|
| bun-version | Bun version or range | latest |
| github-token | token for release lookup | ${{ github.token }} |
| registry-url | optional npm registry | |
| scope | optional scope | |
