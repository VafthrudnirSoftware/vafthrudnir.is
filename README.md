# Vafþrúðnir.is

Static website for [vafþrúðnir.is](https://vafþrúðnir.is) built with
[ssg](https://rgz.ee/ssg.html).

## Building

Grab a copy of the repository and run the following:

```
export PATH="$PWD/bin:$PATH"
ssg5 src/ dst/ 'Vafþrúðnismál' 'https://www.vafthrudnir.is'
```

The built website should be in `dst`.
