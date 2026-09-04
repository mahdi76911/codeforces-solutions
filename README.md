# Codeforces Solutions

125 Codeforces problem solutions, saved as plain text files named
`<problemCode>(<problemTitle>).txt` — e.g. `A1(Theatre Square).txt`.

Mostly Div.2 A/B problems from early contest practice: string manipulation,
simple math, greedy tricks.

## Layout

- `Solution/` — the 125 solutions
- `Test/` — a scratch Visual Studio project used to test code locally

## Build verification

The `Test/` VS solution builds clean with MSBuild + MSVC (SDK 10.0 override,
same as any VS2015-era project). The 125 solution files were additionally
spot-checked: several compile and run with `cl.exe /EHsc /std:c++14`.

### Sample output (real)

**A1 (Theatre Square)** — `m=4, n=7, a=10` → one 10×10 carpet covers the
4×7 theatre:
```
input : 4 7 10
output: 1
```

**A141 (Amusing Joke)** — concatenation check:
```
input : abc  bca  abcabc
output: YES
```
