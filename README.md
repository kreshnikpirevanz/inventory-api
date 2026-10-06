# inventory-api

Inventory service

Owner: `group:default/idp-team` - generated from the **Java Quarkus service** golden path.

- `src/main/java/com/platformpoc/ServiceResource.java` - the REST endpoint (`/`)
- Health checks: `/q/health/live`, `/q/health/ready` (quarkus-smallrye-health)
- `catalog-info.yaml` - how Developer Hub knows about this component
- `devfile.yaml` - how OpenShift Dev Spaces builds a workspace for it
- `deploy/` - OpenShift manifests (S2I build + run), labelled `backstage.io/kubernetes-id: inventory-api`

Local dev: `mvn quarkus:dev`
