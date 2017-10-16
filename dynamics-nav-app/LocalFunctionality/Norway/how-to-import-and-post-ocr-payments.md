---
    title: How to Import and Post OCR Payments 
    description: Before you can receive optical character recognition (OCR) payments, you must make the following preparations:
    
    documentationcenter: ''
    author: SorenGP

    ms.prod: "dynamics-nav-2017"
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 07/01/2017
    ms.author: sgroespe

---
# How to: Import and Post OCR Payments
Before you can receive optical character recognition (OCR) payments, you must make the following preparations:  
  
-   Set up a cash receipt journal template to balance OCR transactions according to the document number, instead of the document type.  
  
-   Import and post the OCR payment files to a cash receipt journal.  
  
### To import OCR payments  
  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cash Receipt Journals**, and then choose the related link.  
  
2.  In the **Batch Name** field, select a journal batch.  
  
    > [!NOTE]  
    >  OCR payments can only be posted to a cash receipt journal that does not use a balance account in the **Bal. Account No.** field on the cash receipt journal line.  
  
3.  On the **Home** tab, in the **Process** group, choose **Import Payments**.  
  
4.  In the **OCR Payment-BBS** window, fill in the fields as described in the following table.  
  
    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |** File Name**|Enter the full path of the import file.|  
  
5.  Choose the **OK** button to import the payment file to the journal.  
  
### To post OCR payments  
  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cash Receipt Journals**, and then choose the related link.  
  
2.  On the **Home** tab, in the **Posting** group, choose **Post**.  
  
     The OCR payment files are posted to the cash receipt journal.  
  
## See Also  
 [Electronic Banking in Norway](electronic-banking-in-norway.md)   
 [How to: Set Up KID Numbers on Sales Documents](how-to-set-up-kid-numbers-on-sales-documents.md)   
 [How to: Set Up OCR Payments](how-to-set-up-ocr-payments.md)   
 Cash Receipt Journal   
 [How to: Fill and Post General Journals](../../../archive/WorkingWithDynamics/how-to-fill-and-post-general-journals.md)   
 [How to: Print the OCR Journal - Test Report](how-to-print-the-ocr-journal-test-report.md)