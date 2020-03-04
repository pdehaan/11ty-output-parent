# 11ty-output-parent

Testing setting the output directory to a parent directory.

## USAGE

```sh
cd nested
npm install
npm run build
cd ..
```

Once the build has finished (and you go back to the parent directory), you should have both a "nested/" directory with our source code, and a "www/" directory with our generated output.

```sh
 tree ./

├── README.md
│
├── nested/ # INPUT DIR
│   ├── .eleventy.js
│   ├── package-lock.json
│   ├── package.json
│   └── src/
│       └── pages/
│           └── index.njk
│
└── www/ # OUTPUT DIR
    └── index.html

4 directories, 6 files
```
