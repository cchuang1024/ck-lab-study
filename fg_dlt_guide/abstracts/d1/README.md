# D1.*

本手冊的第一部份，是進行 DLT 的定義與介紹，共有以下幾個部份：

1. 名詞定義，以及這些詞彙之間的關聯
2. DLT 概論與生態環境介紹
3. DLT 標準制定概況

## 名詞解釋

本章是較為基礎的名詞解釋部份，雖然如此，卻也涵蓋了分散式帳本與區塊鏈領域中的重要詞彙，這部份我用分組的方式來整理，把我認為較特別且概念相近的名詞整理在一起：

### category 1

* consensus
* consensus mechanism
* delegated proof of stack
* proof of work
* proof of stack
* Byzantine fault tolerance

### category 2

* permission
* permissionless
* permissionless distributed ledger system
* public distributed ledger system
* permissioned
* permissioned distributed ledger system
* private distributed ledger system
* hybrid permission

### category 3

* inter ledger interoperability
* intra ledger interoperability
* DLT oracle

### category 4

* decentralized autonomous organizations
* governance

### category 5

* fork
* hard fork
* soft fork

### category 6

* smart contract
* decentralized application
* stateful contract
* stateful execution of contract
* stateless contract
* stateless execution of contract

### category 7

* token
* token ecosystem
* tokenomics (token economic)
* nonfungible token

### category 8

* account
* address
* asset
* wallet
* digital signature
* incentive mechanism

### category 9

* node
* transaction
* block
* genesis block
* blockchain
* subchain

以上是整理我認為較為重要且相關的名詞，然而，在此名詞定義中，我沒有找到 miner (礦工) 的定義，或許在 ITU 的設計哲學裡，這類 DLT 應用與挖礦的區塊鏈有差別。

## 概述與生態環境介紹

本章說明 DLT 的相關特性與生態系：

#### DLT 的特性：

1. append only - 在 DLT 裡，歷史資料是無法更動的，因此只能往上增長
2. immutable - 在 DLT 裡，資料是透過密碼學的方法確保其正確性，因此是不可變的，基於這機制，亦是不可竄改的
3. shared - 在 DLT 裡，資料會在幾乎所有節點中同步、共享，這樣會促進整個鏈的透明性與效率 (當然，這也意味著機敏資料不適合放在 DLT 裡頭)
4. distributed - 分散式的特性使得 DLT 得以容易擴充其規模，並藉著擴充的過程，使得惡意使用者攻擊共識機制的力道變得薄弱，規模越大，DLT 就越可靠