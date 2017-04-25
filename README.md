# repotagger
Personal repo to tag other repos using travis crons.

###### *untoreh/pine*
Tagged `pine-XX.XX-XX` monthly rebuilds the ostree raw alpine-linux image on 
travis-ci.

###### *untoreh/containers*
Tagged `alpbase-XX.XX-XX` monthly rebuilds the alpbase container image on 
`untoreh/alpbase` docker-hub repository. Docker images dependent on `alpbase` are 
built from the `untoreh/containers` docker-hub repository, when a new `alpbase` 
though linked builds to the `/alpbase` repo and through tags, both pushing 
`:basename` tags for the images (container images have no versioning).
