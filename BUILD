docker_image(
  name="should-push",
  instructions=[
    "FROM alpine:3.14",
    "RUN echo 'yes please'"
  ]
)


docker_image(
  registries=["@prod"],
  name="no-push",
  instructions=[
    "FROM alpine:3.14",
    "RUN echo 'no thanks'"
  ]
)
