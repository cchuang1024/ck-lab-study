# Overview and Glossary

## Trusted Digital Identity Framework ("TDIF")

### Abstract



### Introduction

#### 關鍵詞彙

* DTA, Digital Transformation Agency, 隸屬於澳洲總理與內閣轄下，獨立運作之數位轉型機構 [[1]](https://www.directory.gov.au/portfolios/services-australia-part-social-services-portfolio/digital-transformation-agency)
* private sector, 私部門, e.g. 民間企業
* digital identity system, 數位化身份識別系統, identity 特別指的是 "個人身份識別"
* identity federation, 按複合名詞的解釋方式，應為 "身份識別的聯盟"
* TDIF, trusted digital identity framework, 一套用來實作 identity federation 的框架
* accredited provider, 正式認可的提供者 (推斷應是 "身份識別服務")
* applicant, 申請者 (推斷應是 "服務申請者")
* relying party, 相依參與者
* accreditation authority, 認證權責機關

#### 本章大意

本章是整部文件的總綱，講到這份文件的源頭 (DTA)，以及這份文件的主題 (TDIF)，並且說到這份文件涵蓋到的內容 (範圍, 目的, 關鍵詞彙定義)，並這份文件的目標讀者 (供應者、申請者、參與者、權責機關)

### Context

#### 關鍵詞彙

* UNCITRAL, United Nations Commission on International Trade Law, 聯合國國際貿易法委員會
* authoritative source, 權威來源 (指具身份識別的發布與詮釋權機構)
* a group of participating entities, 一群參與的個體
* identity attribute information, 身份識別屬性資訊
* identity transaction, 身份識別交易 (transaction 另一解釋是協議，但不確定哪個合適)
* syndicated, 聯合的，原指一稿多投的行為，引伸為同本質，但具有多個身份認證管道，類似 SSO 概念
* federated, 聯盟的，對比 syndicated，指的是不同本質，但互相承認的身份認證機制
* decentralized, 去中心化，在此指身份識別不是由統一的權威機構管理
* identity provider, 身份識別提供者
* bilateral agreements, 雙邊協議
* Service Level Agreements, 服務等級協議
* a federated identity system, 一個聯盟性的身份識別系統
* functionality, 功能性
* trustworthiness, 可信度
* trust framework, 信任框架

#### 本章大意

本章基於聯合國國際貿易法協會對身份識別系統的定義來說明，其中結尾說到，身份識別系統會支配、指導著 (governing) 對於個人、法人、裝置、以及數位物件的身份識別屬性資訊 (identity attribute information) 的收集、驗證、儲存、交換、認證、信任等過程；並且身份識別系統的目的旨在促進身份識別交易。(其實這段很難讀懂，目前只能照字面上翻譯的結果進行理解。)

接著說到，身份識別系統有兩種分類，一個是 Syndicated，聯合式的，在這模式之下，身份識別的方式像是 single sign on (SSO) 的機制，另一種是 Federated，聯盟式的，在這模式之下，身份識別的方式是去中心化的機制，使用者可以自行決定所使用的身份識別提供者的服務，來存取公部門、私部門的各個服務。

對比聯盟式的，傳統聯合式的識別機制顯得侷限且不透明，難以應用在國家層級的場景中，而聯盟式的機制，透過信任框架 (trust framework) 就相較地有效率且容易擴充。

最後，信任框架的內涵，在於為了要能治理聯盟式身份識別系統，所包含的法規約束力、議定的技術規格、規章，以及協議等規範內容，以使得參與者皆能達到共通的產出。(這樣的說明不太確定)

而信任框架最重要的兩個特性，就是功能性與可信度。

### Characteristics of a trust framework

#### 關鍵詞彙

* Open Identity Exchange, Google、PayPal、Equifax、VeriSign、Verizon、CA 及 Booz Allen Hamilton等業者共組之「開放身份交換組織」[[2]](https://www.ithome.com.tw/node/59890), [[3]](https://www.trademag.org.tw/page/newsid1/?id=712222&iz=6)
*  digital verification, 數位驗證
* binding of a person, 對特定人的綁定
* authentication credentials, 對憑證的認證
* proper operation, 正確地運作
* compliance, 合規, 適法性
* in accordance with legislative and regulatory requirements, 合乎立法與監管單位 (我想原文應該省略了政府單位這一對象) 的要求
* legal certainty and predictability, 法律上的確定性與可預測性
* transparency, 透明性

#### 本章大意

本章旨在說明一個信任框架 (trust framework) 應當有些什麼樣的特性，作者引申 OIX 組織對 trust framework 的定義方式進行陳述，如下列說明：

1. 範圍：信任框架就是透過聯盟式的身份識別系統來發揮以下三種作用：
   1. 數位化驗證每個人的身份
   2. 將每個人綁定到憑證系統上
   3. 讓每個人可以透過自己的憑證使用相關單位的服務
2. 目的：信任框架的透過定義與管理的方法，使得身份識別系統具有足夠的功能性與可信度，而從可信度的角度來看，信任框架處理了以下議題：
   1. 功能性，信任框架必須確保這身份識別系統的運作正確性，以及適法性
   2. 可信度，信任框架提供了風險管理措施、法律上的確定性與可預測性，以及透明性的特性來促進它本身的可信度
3. 內涵：信任框架的內涵有二，(雖然在本文裡，內涵是放在目的小節下，但在 OIX 原文裡，這一節與目的是同級別的內容，故獨立出來說明。)
   1. 定義角色與功能
   2. 討論關鍵議題
4. 綁定：將參與者與實際的法規、合約綁定起來

### Trusted Digital Identity Framework

#### 關鍵詞彙

* Financial System Inquiry, 財務系統調查, 2013-2014 之澳洲財政發展策略研究計畫 [[4]](https://treasury.gov.au/publication/c2014-fsi-final-report)
* jurisdictions, 
* be accredited, 
* advocate, 
* digital identity verification process,
* ongoing accreditation obligation, 
* Trusted Federated Digital Identity System, 可信的聯盟式數位身份認證系統

#### 本章大意

本章是整個 TDIF 說明的核心，文件的說明脈絡從 TDIF 的緣起、願景開始，建立指導原則，並設定目標、角色與系統功能性規格，文件清單及慣例、開發時程，並定義服務提供者之認可機制、治理模型。

以下列出這整段值得注意的幾件事：

1. 在 TDIF 的願景 (_What TDIF success will look like_) 一節，本文從質性、量性以及參與者的三個角度進行陳述，質性角度來看，TDIF 提供了使用者兩個層面的特性：

   1. 第一是簡單、安全、自由地建立身份識別機制
   2. 第二是安全地在政府服務中使用這個機制

   這兩個特性幾乎貫穿整個 TDIF 的原則與各樣的目標。
   
2. TDIF 指導原則裡，列了八項原則，以下會說明這八項原則，但值得關注的是，第一項原則是使用性，以使用者為中心。作為一個政府數位化服務的設計，TDIF 第一個原則就是容易、方便、簡化，並提供民眾充足的自由度選擇服務提供者，且考量到民眾在不同層面下的身份識別需求而設計出相關的彈性，這一大項原則其實非常重要。

3. TDIF 的功能性規範裡，其定義的方式大多參考 OIX 的架構與脈絡，而在角色定義上，則從各個層面進行完整的命名與規範，這部份會在下列內容中說明。在此可以從一個完整的框架內看見要建構一套完整的 federated identity system，需要考量到哪些的 stackholders。

4. TDIF 的認可機制裡，分為第一次進行的認可，以及往後每年進行的認可要求。亦即服務提供者第一次認可通過之後，仍然每年都必須檢視自己提供的系統與服務是否合乎 TDIF 的要求與規範。

#### TDIF 指導原則

TDIF 的指導原則，列出許多重要的設計精神，例如易用、平等、公正、自由、安全、責任等，簡述如下：

**1. 以使用者為中心**

* 服務必須提供容易、方便、簡化的使用方式
* 民眾可以自由選擇自己想要的服務供應者，不論公私部門，只要這些供應者都能通過政府認證的流程
* 民眾不只可以選擇自己想選擇的供應者，更可以選擇多個不同的供應者提供各個層面的身份識別與認證服務
* 民眾可以區分公私不同的身份，或把這兩種身份合併

**2. 自願性**

* 民眾可以自己決定要不要參加聯盟式身份識別服務
* 當民眾決定自己要參加，他能用最直接了當的方式來控制他自己的身份識別資訊
* 民眾自己的認證紀錄，自己可以輕易地存取，並會被供應者妥善保管

**3. 服務傳達性**

* 政府認可的供應者須提供足夠的選擇與便利給民眾
* 參與廠商對於民眾的供應價格必須保持中立 (不因特別的人給予特別的價格)
* TDIF 所衍生的商業模式必須能激勵民間企業的參與

**4. 強化隱私保護**

* 個人資料的生命週期(收集、使用、銷毀)必須基於個人資料保護法令以及良好的實務作法之下運作
* 強化隱私保護的作為，會平等地作用在每一個民眾的資料上
* 政府及供應商須履行完善告知民眾，對其個人資料之使用與保護的措施
* 民眾可以自由地看到自己暴露給政府與供應者的資料，並且能自主地決定內容的修正或回收

**5. 協作性**

* TDIF 應活化公、私部門及社群間的合作，以運用各方的力量、政府及企業的專業能力，並反映出聯盟式身份識別系統的強度

**6. 互通性**

* 使用相關的開放標準、框架，及通用方法，以促進與國內、國際間其他識別系統的互通性

**7. 適應性**

* 促進技術與商業模式之彈性及創新
* 對於社群、企業及政府日新月異的需要，TDIF 須具有足夠的彈性以進行演進
* 從安全的角度進行架構設計，以保護各類高低價值以及不同層級使用者之交易

**8. 安全與彈性**

* 在 TDIF 裡各種角色，皆須符合最低之安全要求才能提供服務
* 而同樣的安全要求，亦會用來規範政府方的單位必須達到
* 資安威脅與風險必須由認可的供應者自己進行管理 (風險自負原則)
* 必須建構、維護一套有效的詐騙防範控制措施

#### 目標

從指導原則發展而來，TDIF 有四大目標：

1. 簡單易用
2. 無障礙性
3. 安全且保護隱私
4. 基於公開標準

這四個目標中，安全且保護隱私的目標內容最多，應是整個 TDIF 的關鍵核心，以下列舉此目標的說明：

* No single identifier is issued to relying parties or identity service providers.
* People can interact with any relying party without an identity service provider being able to observe what service they are using (and vice versa).
* The identity service provider and relying party are prevented from tracking people using policy and technical means.
* There is no single digital authentication credential or centralised database of personal information.
* People are given greater control over their personal information and who their personal information is shared with.

#### 角色與功能

TDIF 的功能層面，分為營運類功能與參與類功能，此分類模式大略根據 OIX 進行分類，而分類定義完之後，更進一步將列舉的功能內容，分別設定給不同的角色來負責。因此先說明 TDIF 的角色定義：

* Identity Service Providers (IdP): 負責管理識別服務、授權內容，及相關存取紀錄等
* Credential Service Providers (CSP): 負責管理認證憑證及相關存取紀錄等，這個角色與 IdP 關係較緊密，也可能與 IdP 合在一起
* Attribute Providers: 負責管理身份屬性以及相關的紀錄
* Identity Exchanges: 負責進行認證 (authentication)，並管理相關的存取紀錄等。
* Relying Parties: 依賴著 IdP、Attribute Providers、Identity Exchanges 進行認證、授權、提供屬性資料，藉以為民眾開通其數位服務之政府與機構 (如，稅務機關的線上繳稅)
* The public: 參與在聯盟式身份識別系統裡的民眾
* Attribute Verification Services: 又為 Authoritative Sources，此為連接到識別系統中，藉以卻認識別屬性以及相關資訊的資料庫

#### 識別聯盟治理模型

