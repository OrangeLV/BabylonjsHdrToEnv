This can be used to convert `.hdr` environment maps to `.env` maps which
are better suited for the web.

```
npm install
NODE_OPTIONS=--openssl-legacy-provider npm run build
cd www/
python3 -m http.server
```

Go to `localhost:8000` and drop in the `.hdr` file.
