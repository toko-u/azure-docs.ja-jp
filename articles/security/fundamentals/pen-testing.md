---
title: 侵入テスト | Microsoft Docs
description: この記事では、侵入テスト プロセスの概要と、Azure インフラストラクチャで実行されているアプリに対して侵入テストを行う方法について提供します。
services: security
documentationcenter: na
author: TerryLanfear
manager: barbkess
editor: TomSh
ms.assetid: 695d918c-a9ac-4eba-8692-af4526734ccc
ms.service: security
ms.subservice: security-fundamentals
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 08/13/2018
ms.author: terrylan
ms.openlocfilehash: db6e25b6304ee9ac41ca95d5a3a6eac0e91eb41b
ms.sourcegitcommit: dccb85aed33d9251048024faf7ef23c94d695145
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/28/2020
ms.locfileid: "87287770"
---
# <a name="penetration-testing"></a>侵入テスト
アプリケーションのテストとデプロイに Azure を使用するメリットの 1 つが、環境をすばやく作成できることです。 オンプレミスのハードウェアの要求、取得、および “ラックとスタック” に関して心配する必要はありません。

これは非常に良いことですが、通常のセキュリティで適切な注意を払う必要はあります。 多くの場合に必要となる操作の 1 つは、Azure にデプロイするアプリケーションに対する侵入テストです。

Microsoft が [Azure 環境の侵入テスト](https://gallery.technet.microsoft.com/Cloud-Red-Teaming-b837392e)を実行していることは、既にご存知かもしれません。 これは Azure の向上を促進するうえで役に立ちます。

お客様のためにアプリケーションの侵入テストを行うことはありませんが、お客様のアプリケーションにテストを実行する必要があることは理解しています。 お客様のアプリケーションのセキュリティを強化するときに、Azure エコシステム全体のセキュリティ保護を高めることができるため、これは良いことです。

2017 年 6 月 15 日時点で、Microsoft は Azure リソースに対する侵入テストを実施する際に事前承認を求めなくなりました。 Microsoft Azure に対する今後の侵入テストの契約を正式に文書化することをご希望のお客様は、[Azure サービス侵入テスト通知フォーム](https://portal.msrc.microsoft.com/en-us/engage/pentest)に記入することをお勧めします。 このプロセスは Microsoft Azure にのみ関連するものであり、その他の Microsoft Cloud サービスには適用されません。

>[!IMPORTANT]
>侵入テストのアクティビティを Microsoft に通知する必要はなくなりましたが、お客様は「[Microsoft Cloud Unified Penetration Testing Rules of Engagement (Microsoft Cloud 統合侵入テストの活動規則)](https://technet.microsoft.com/mt784683)」に引き続き従う必要があります。

実行できる標準テストは、次のとおりです。

* [Open Web Application Security Project (OWASP) の上位 10 の脆弱性](https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project)
* [ファジー テスト](https://cloudblogs.microsoft.com/microsoftsecure/2007/09/20/fuzz-testing-at-microsoft-and-the-triage-process/)
* [ポートのスキャン](https://en.wikipedia.org/wiki/Port_scanner)

## <a name="next-steps"></a>次のステップ

- Microsoft Azure でホストされているアプリケーションに対して今後実行する予定の侵入テストを正式に文書化したい場合は、[エンゲージメントの侵入テスト ルール](https://www.microsoft.com/msrc/pentest-rules-of-engagement?rtc=2)に関するページに進み、テスト通知フォームに情報を入力してください。
