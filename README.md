# ChainX Genesis

ChainX 三次创世节点大赛总得分排名前 25 的节点将有幸成为 ChainX 主网的创世节点，最终排名见: [chainx-genesis-competition-final-result.csv](https://gist.github.com/liuchengxu/10db5920590454d7b5fb5feaf2769fc6#file-chainx-genesis-competition-final-result-csv)。

如何提交 ChainX 主网创世节点:

1. fork 本仓库。

2. clone fork 的仓库, 复制 `genesis_example.json` 并重命名为 `genesis_<Your Name>.json`。

3. 在 `genesis_<Your Name>.json` 中填入创世节点相关信息。

    ```json
    {
        "account_id": "",
        "session_key": "",
        "name": "",
        "url": "",
        "about": ""
    }
    ```

    - `account_id`: 节点账户公钥。
    - `session_key`: 节点出块公钥。
    - `name`: 注册节点名，注意该名称不可更改。
    - `url`: 节点网址。
    - `about`: 节点关于信息。

    将账户地址粘贴到浏览器 https://scan.chainx.org 即可看到账户公钥。

4. 向本仓库 https://github.com/chainx-org/ChainX-genesis 发起 Pull Request 提交创世节点信息。
