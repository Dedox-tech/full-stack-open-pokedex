# Considerations about CI/CD process in GO

Setting a CI/CD pipeline for a web application written in GO might include the following steps: First, we need to use a linter, which is usually Golangci-Linter. For testing, the standard library could work, but a specific framework like Testify will be better.  Finally, the build can be achived with a separate solution as Go-Task or GNU-Make.

Besides Jenkins and GitHub Actions, CircleCI is another option for setting up the CI/CD in Golang apps. CircleCI supports building Go projects using any version of Go that can be installed in a Docker image.

With CircleCI, we have the choice of going for a self-hosted route, or for a cloud-based one. For starting up in the platform, we can start building for free in the cloud solution, and see if it meets the need of the project. After that, we can contact CircleCI sales for a quote of running the platform in your personal server.
