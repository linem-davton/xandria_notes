# Part I. Foundations of Data Systems

## Describing Performance

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_54e2cd66-3eff-451d-a065-3d2a311b478b","annotationId":"ann_98b60d58-0055-4309-a7b1-a5d2ca29bc3a","sourceUpdatedAt":"2026-05-07T01:10:13.932Z"} -->
In order to figure out how bad your outliers are, you can look at higher percentiles: the 95th, 99th, and 99.9th percentiles are common \(abbreviated p95, p99, and p999\). They are the response time thresholds at which 95%, 99%, or 99.9% of requests are faster than that particular threshold. For example, if the 95th percentile response time is 1.5 seconds, that means 95 out of 100 requests take less than 1.5 seconds, and 5 out of 100 requests take 1.5 seconds or more. This is illustrated in Figure 1-4.

[Page 37](xandria://reader/annotation?readableId=read_54e2cd66-3eff-451d-a065-3d2a311b478b&annotationId=ann_98b60d58-0055-4309-a7b1-a5d2ca29bc3a)
<!-- xandria:highlight:end -->

## The Object-Relational Mismatch

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_54e2cd66-3eff-451d-a065-3d2a311b478b","annotationId":"ann_c18116dd-cc38-4214-85f9-0122a44671b1","sourceUpdatedAt":"2026-05-07T14:07:17.639Z"} -->
The JSON representation has better locality than the multi-table schema in Figure 2-1. If you want to fetch a profile in the relational example, you need to either perform multiple queries \(query each table by user\_id\) or perform a messy multi￾way join between the users table and its subordinate tables. In the JSON representa‐ tion, all the relevant information is in one place, and one query is sufficient.

[Page 54](xandria://reader/annotation?readableId=read_54e2cd66-3eff-451d-a065-3d2a311b478b&annotationId=ann_c18116dd-cc38-4214-85f9-0122a44671b1)
<!-- xandria:highlight:end -->

## Graph-Like Data Models

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_54e2cd66-3eff-451d-a065-3d2a311b478b","annotationId":"ann_e8a3ea70-a07d-4fca-8451-4195726e8fae","sourceUpdatedAt":"2026-05-07T18:29:20.197Z"} -->
We saw earlier that many-to-many relationships are an important distinguishing fea‐ ture between different data models. If your application has mostly one-to-many rela‐ tionships \(tree-structured data\) or no relationships between records, the document model is appropriat

[Page 71](xandria://reader/annotation?readableId=read_54e2cd66-3eff-451d-a065-3d2a311b478b&annotationId=ann_e8a3ea70-a07d-4fca-8451-4195726e8fae)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_54e2cd66-3eff-451d-a065-3d2a311b478b","annotationId":"ann_cd17c914-f439-443d-8cef-2cbae58bb68e","sourceUpdatedAt":"2026-05-07T18:34:03.188Z"} -->
A graph consists of two kinds of objects: vertices \(also known as nodes or entities\) and edges \(also known as relationships or arcs\). Many kinds of data can be modeled as a graph. Typical examples include:

[Page 71](xandria://reader/annotation?readableId=read_54e2cd66-3eff-451d-a065-3d2a311b478b&annotationId=ann_cd17c914-f439-443d-8cef-2cbae58bb68e)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_54e2cd66-3eff-451d-a065-3d2a311b478b","annotationId":"ann_4e248721-af59-4e4e-9cf6-4662d15a84b4","sourceUpdatedAt":"2026-05-07T18:35:12.855Z"} -->
In this section we will use the example shown in Figure 2-5. It could be taken from a social network or a genealogical database: it shows two people, Lucy from Idaho and Alain from Beaune, France. They are married and living in London.

[Page 71](xandria://reader/annotation?readableId=read_54e2cd66-3eff-451d-a065-3d2a311b478b&annotationId=ann_4e248721-af59-4e4e-9cf6-4662d15a84b4)
<!-- xandria:highlight:end -->