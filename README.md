# web3-uploader

A React library to help developers add files upload feature to web3 world - IPFS/Filecoin easily.

## How to use

```bash
<Web3Uploader
  apiToken="WEB3.STORAGE-TOKEN"
  onUploaded={handleUploaded}
  onLoading={handleLoading}
/>
```

* `apiToken` The web3.storage token.

* `onUploaded` The callback once all files uploaded to IPFS/Filecoin

* `onLoading` The loading status

* `accept` Set accepted file types. One of type: string, string[]

* `maxFiles` Maximum accepted number of files The default value is 0 which means there is no limitation to how many files are accepted.

* `disabled` Enable/disable the dropzone.

* `canUpload` Whether the web3 uploader can upload the files to IPFS/Filecoin.