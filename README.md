# taikai

Generated via copier from github.com/catalystsquad/copier-go-cobra-app

In order to run this code you will need the following on your path:
- buf
- Go 1.21+
- Node 18+ (and npm of course)
- Java of some kind (for the OpenAPI Client Generator)
- bash, which you should just have anyway


# Running

If using protos and the protos have not been built or are not up to date, you will be sad. `./tools.sh build_protos` will handle that.

If you use skaffold, make sure you have the helm repos added (look at skaffold.yaml for the command to run to do so).

Otherwise, you can `./tools.sh run` or `skaffold dev` if you prefer. Running via tools will run it with `go` and skaffold will run in a kubernetes cluster.

