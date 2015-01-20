This is a collection of miscellaneous system utilities.  This image is
designed primarily for use an Atomic host, and is most useful when run
like this:

    docker run --rm -ti \
      --net=host \
      --pid=host \
      --privileged \
      -v /:/host \
      command [args]

