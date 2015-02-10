# omega-sqrt

Initial test package for Ωpm ("omega package manager"), returning square roots.

## Concept

Ωpm is an end-to-end JavaScript package manager with verified builds.

Concept: https://gist.github.com/mapmeld/7eb3b213358b55b74bdf

## Usage

### Securely install the package
```
Ωpm set-key YOUR_PUBLIC_KEY
Ωpm install omega-sqrt@[SHA]
```

### Running in Node.js
```
node
> sqrt = Ω("omega-sqrt", "[SHA]").sqrt;
{ }
> sqrt(4)
2
```

## License

GPLv3+ License
