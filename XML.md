
**Introduction to XML | What is XML, XPath, XML Namespace, XSLT and XSD?
**

<img width="837" height="385" alt="image" src="https://github.com/user-attachments/assets/ae2b5e40-467d-4f6f-8d7d-94addc2a7859" />


XML represent data in a clean structured  tree like format. We can see parent-child relationship, even child and grand-child relation ship, even deeper relationships. The tags are not pre-defined.


<img width="1024" height="483" alt="image" src="https://github.com/user-attachments/assets/00a7d131-1c2a-4167-87ef-e6f1567f6b01" />


Here is a sample of XML file

<img width="824" height="476" alt="image" src="https://github.com/user-attachments/assets/82c24993-b5af-41ce-8523-fe86984b72d9" />



Every XML files need a root node and in the above given file 'Book' is the root node. Under the root node, child nodes(say for example <name>, <price>) will come.

Every node must have a opening and closing tag.

Anything written between these tags are known as 'Values'.


<img width="974" height="599" alt="image" src="https://github.com/user-attachments/assets/2f3e9ad5-365f-4d40-b33f-8503e05240fe" />

Self closing tag: They jst have a closing tag. It means that that node does not contain any values.


**XPATH
**

This is very important because the routing between XML elements and filter conditions are applied using XPath.
<img width="922" height="579" alt="image" src="https://github.com/user-attachments/assets/8fcd8ce9-a5a8-4ec2-a14d-0bd37cf06d53" />



<img width="750" height="510" alt="image" src="https://github.com/user-attachments/assets/df6ce920-eb2e-4734-bd75-178e71484d1d" />

**
XML Namespace**

In the below example, we have 'Name' tag twice, so the absolute path will give Ramesh or Suresh? This is a name conflict.
<img width="669" height="458" alt="image" src="https://github.com/user-attachments/assets/4343f879-43cd-4b75-a638-ae50794fd60d" />


To avoid the naming conflict which might raise from XML tags are resolved by Namespace.

NOTE: The namespace URI need not to be a working URL, it could be a random unique one.

<img width="796" height="438" alt="image" src="https://github.com/user-attachments/assets/5e0987c9-1f34-4ef4-92ea-f6acd34f1ea5" />

**
XSLT**


<img width="940" height="568" alt="image" src="https://github.com/user-attachments/assets/0b69b082-443f-4d14-8fc5-f775831e4de9" />


<img width="1040" height="585" alt="image" src="https://github.com/user-attachments/assets/b30e6fc4-087d-42b4-a4f8-9bd24f1ac4a4" />

This can be acieved by the below XSLT

<img width="1093" height="461" alt="image" src="https://github.com/user-attachments/assets/e6511aa4-16b4-498c-81c4-671c70774f87" />

**
XSD**


<img width="931" height="580" alt="image" src="https://github.com/user-attachments/assets/e74905b9-3ac2-408b-97ec-05ba41884923" />

We can define the order of elements, how many times they can appear, type of elements like string or number etc,.
<img width="861" height="562" alt="image" src="https://github.com/user-attachments/assets/6044f61a-afc0-4426-8010-c302cd13c4c8" />
