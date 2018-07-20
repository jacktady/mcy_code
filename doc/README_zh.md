# <center>MCY</center>

> MCY是一个基于以太坊的代币

官网地址：[海环链](http://www.mcy-chain.com/)

1. 代币基于TokenERC20创建，满足TokenERC20格式

``` javascript
    function TokenERC20(uint256 initialSupply, string tokenName, string tokenSymbol, uint8 tokenDecimals) public {
        name = tokenName;
        symbol = tokenSymbol;
        decimals = tokenDecimals;
        totalSupply = initialSupply * 10 ** uint256(decimals);
        balanceOf[msg.sender] = totalSupply;
    }
```

2. MCY 保证不再进行增发

3. MCY 发行总量为三亿个

## 发行说明

肯尼亚内罗毕威德利尔集团公司成立于1962年，主要经营跨国贸易，港口运输、金融业，服务业和科技领域等业务。基于集团区位和科技优势，2015年初，受联合国环境保护规划署委托，开始关注并研究海洋环境与生物保护领域问题。2017年12月，联合国环境保护规划署正式授权我公司，结合区块链技术，开始着手海洋生态的落地保护工作。2018年6月，海洋生态保护工作正式启动。

[English DOC](../README.md)