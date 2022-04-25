# Nikto

[Nikto](https://github.com/sullo/nikto) vulnerability scanner docker image.

## Usage

```bash
# Create a shell alias
$ alias nikto='docker run --rm -it -v $PWD:/out --network host dannyben/nikto'

# Verify it is working
$ nikto --help

# Scan some sites
$ nikto -h localhost -p 3000 -o /out/report.htm
```