---
layout: post
title: "5G Authentication"
data: 2021-01-14 12:00:00 +0800
catagories: 5G
---
This serial of article will focue on 5G Authentication. Fot the first article, I will briefly go through the difference between 4G and 5G.



<table border="1">
	<caption>4G and 5G's comparision</caption>
	<tr>
		<th></th>
		<th>4G</th>
		<th>5G</th>
	</tr>
	
	<tr>
		<th>UE</th>
		<td>USIM</td>
		<td>USIM</td>
	</tr>
	<tr>
		<th rowspan=2>UE's ID</th>
		<td>UE->SN: IMSI/GUTI</td>
		<td>UE->SN: SUCI/5G-GUTI</td>
	</tr>
	<tr>
		<td>SN->HN: IMSI</td>
		<td>SN->HN: SUCI/SUPI</td>
	</tr>
	<tr>
		<th>SN' ID</th>
		<td>SN_id(MCC+MNC)</td>
		<td>SN_name(5G:MCC+MNC)</td>
	</tr>
	<tr>
		<th> Trust_model</th>
		<td>Shared Symmectic Key</td>
		<td>Shared Symmectic Key</td>
	</tr>
</table>
