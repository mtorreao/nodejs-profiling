# Node.js CPU Profiling

## Install

```bash
npm install
npm install -g autocannon
```

## Run benchmark

Run code

```bash
node index.js
```

Run autocannon

```bash
autocannon http://localhost:3000/issue
```

Use the result file *.cpuprofile in the CPUPro site to inspect.

Compare with the route 'no-issue'

```bash
autocannon http://localhost:3000/no-issue
```

## Check cpu profile

Go to [https://discoveryjs.github.io/cpupro/](https://discoveryjs.github.io/cpupro/) and upload the cpu profile file.

