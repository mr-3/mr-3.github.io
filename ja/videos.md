---
layout: ja_page
title: 動画
permalink: /ja/videos
---

[RDF Primer](https://www.w3.org/TR/2004/REC-rdf-primer-20040210/) [Example 1](https://www.w3.org/TR/2004/REC-rdf-primer-20040210/#example1): RDF/XML Describing Eric Miller

    <?xml version="1.0"?>
    <rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
           xmlns:contact="http://www.w3.org/2000/10/swap/pim/contact#">
        <contact:Person rdf:about="http://www.w3.org/People/EM/contact#me">
          <contact:fullName>Eric Miller</contact:fullName>
          <contact:mailbox rdf:resource="mailto:em@w3.org"/>
          <contact:personalTitle>Dr.</contact:personalTitle>
        </contact:Person>
    </rdf:RDF>

## デモ動画1（トップダウン）
<div style="text-align: center;"><iframe width="500" height="400" src="https://www.youtube.com/embed/kmgZxMg6a9c" frameborder="0" allowfullscreen></iframe></div>

## デモ動画2（ボトムアップ）
<div style="text-align: center;"><iframe width="500" height="400" src="https://www.youtube.com/embed/HXfgCO8pefU" frameborder="0" allowfullscreen></iframe></div>

[RDF Primer](https://www.w3.org/TR/2004/REC-rdf-primer-20040210/) [Example 14](https://www.w3.org/TR/2004/REC-rdf-primer-20040210/#example14): RDF/XML for a Bag of Students

    <?xml version="1.0"?>
    <rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
             xmlns:sv="http://example.org/students/vocab#">
       <rdf:Description rdf:about="http://example.org/courses/6.001">
          <sv:students>
             <rdf:Bag>
                <rdf:li rdf:resource="http://example.org/students/Amy"/>
                <rdf:li rdf:resource="http://example.org/students/Mohamed"/>
                <rdf:li rdf:resource="http://example.org/students/Johann"/>
                <rdf:li rdf:resource="http://example.org/students/Maria"/>
                <rdf:li rdf:resource="http://example.org/students/Phuong"/>
             </rdf:Bag>
          </sv:students>
       </rdf:Description>
    </rdf:RDF>


## デモ動画3
<div style="text-align: center;"><iframe width="500" height="400" src="https://www.youtube.com/embed/08W4e5cIS-A" frameborder="0" allowfullscreen></iframe></div>
