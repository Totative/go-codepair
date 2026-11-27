FROM gcr.io/oss-fuzz-base/base-builder-go:v1@sha256:0ebd94f573c7917b93a7edc8cd1db21c167adbd1d9c59943c3ebe4afb7aa4497
COPY . $SRC/go-codepair
WORKDIR $SRC/go-codepair
COPY .clusterfuzzlite/build.sh $SRC/build.sh
