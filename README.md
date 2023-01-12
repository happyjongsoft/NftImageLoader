# NFT Image Loader on Unity3D

## Screenshots

![Screenshot](https://github.com/happyjongsoft/NftImageLoader/blob/master/Screenshot_1.png?raw=true)

![Screenshot](https://github.com/happyjongsoft/NftImageLoader/blob/master/Screenshot_2.png?raw=true)

## Edit chain, network, contract's address and token's id
```
    //The chain to interact with
    private string chain = "ethereum";
    //The network to interact with
    private string network = "goerli";
    //Contract to interact with
    private string contract = "0xd5b3d473c2379f471011e20edf2bd40c66158b97";
    //Token ID to pull from contract
    private string tokenId = "0";
```

## To display on RawImage UI Controller of Unity3D
```
	GetComponent<RawImage>().texture = texture;
```

## To display on MeshRenderer 
```
	GetComponent<MeshRenderer>().material.mainTexture = texture;
```

Email [happy.jong.soft@gmail.com](mailto:happy.jong.soft@gmail.com)
