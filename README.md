### Generics in go

A new golang environment (dev.go2go) was downloaded and compiled.

In order to run the code:
```
go tool go2go run <file.go2>
```

I have some issues with using packages (something is wrong with my GOPATH etc), so I put all the code-snippets in different main-routines. The point is to try out the
generics in go that might be introduced in go 1.17.

I basically try to implement some code that appears in the "Type Parameters - Draft Desgn", https://go.googlesource.com/proposal/+/refs/heads/master/design/go2draft-type-parameters.md.