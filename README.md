# How to run
* Put some files in this project directory.
  * json metadata filenames should be in <64_char_nums>.json (see [Openzeppelin ERC1155 docs](https://docs.openzeppelin.com/contracts/3.x/erc1155))

* Go to https://moralis.io/, login, create server, and copy CLI API Key and CLI API Secret

* run a command in one terminal
```
docker-compose up
```

* run the following commands in another terminal
```
$ docker exec -it nftapp sh

$ npx moralis-admin-cli deploy

Specify Moralis Api Key: ...
Specify Moralis Api Secret: ...

Deployed successfully!
Site is available at: https://{some_chars}.usemoralis.com

```

* see your deployed files on https://{some_chars}.usemoralis.com/{filename.ext} (example: https://{some_chars}.usemoralis.com/photo.png)