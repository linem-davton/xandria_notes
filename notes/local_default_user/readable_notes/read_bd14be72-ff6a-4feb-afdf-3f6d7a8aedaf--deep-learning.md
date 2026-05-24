# 2.9 The Moore-Penrose Pseudoinverse

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf","annotationId":"ann_5b8f1f40-3173-461b-9c1f-2664f93b0e18","sourceUpdatedAt":"1777611338227"} -->
If A is taller than it is wide, then it is possible for this equation to have no solution. If A is wider than it is tall, then there could be multiple possible solutions.

[Page 66](xandria://reader/annotation?readableId=read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf&annotationId=ann_5b8f1f40-3173-461b-9c1f-2664f93b0e18)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf","annotationId":"ann_60731373-db1b-4bc8-991b-926a3032db83","sourceUpdatedAt":"1777611338227"} -->
A+ = V D+U

[Page 66](xandria://reader/annotation?readableId=read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf&annotationId=ann_60731373-db1b-4bc8-991b-926a3032db83)
<!-- xandria:highlight:end -->


# 2.10 The Trace Operator

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf","annotationId":"ann_abb1eb35-6013-47f1-b251-906f46b3ddf3","sourceUpdatedAt":"1777611338227"} -->
U, D and V are the singular value decomposition of A, and the pseudoinverse D+ of a diagonal matrix D is obtained by taking the reciprocal of its nonzero elements then taking the transpose of the resulting matrix.

[Page 67](xandria://reader/annotation?readableId=read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf&annotationId=ann_abb1eb35-6013-47f1-b251-906f46b3ddf3)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf","annotationId":"ann_e5a78e09-f47d-46e5-8cd1-34cc27d8f327","sourceUpdatedAt":"1777611338227"} -->
When A has more columns than rows, then solving a linear equation using the pseudoinverse provides one of the many possible solutions.

[Page 67](xandria://reader/annotation?readableId=read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf&annotationId=ann_e5a78e09-f47d-46e5-8cd1-34cc27d8f327)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf","annotationId":"ann_c94f5fb8-9a8b-48f6-8ce1-92561af57a9d","sourceUpdatedAt":"1777611338227"} -->
Euclidean norm

[Page 67](xandria://reader/annotation?readableId=read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf&annotationId=ann_c94f5fb8-9a8b-48f6-8ce1-92561af57a9d)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf","annotationId":"ann_6ba6ea44-9835-4b55-968c-891d8dd1dd30","sourceUpdatedAt":"1777611338227"} -->
When A has more rows than columns, it is possible for there to be no solution.

[Page 67](xandria://reader/annotation?readableId=read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf&annotationId=ann_6ba6ea44-9835-4b55-968c-891d8dd1dd30)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf","annotationId":"ann_ed328d46-81b6-46a8-a9f2-a6cc326c7acb","sourceUpdatedAt":"1777611338227"} -->
In this case, using the pseudoinverse gives us the x for which Ax is as close as possible to y in terms of Euclidean norm

[Page 67](xandria://reader/annotation?readableId=read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf&annotationId=ann_ed328d46-81b6-46a8-a9f2-a6cc326c7acb)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf","annotationId":"ann_e609bd19-64d2-48a1-af0a-a33bff631141","sourceUpdatedAt":"1777611338227"} -->
Frobenius norm of a matrix:

[Page 67](xandria://reader/annotation?readableId=read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf&annotationId=ann_e609bd19-64d2-48a1-af0a-a33bff631141)
<!-- xandria:highlight:end -->


# 2.12 Example: Principal Components Analysis

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf","annotationId":"ann_d2463093-7d07-426c-952a-2a6179bd3de8","sourceUpdatedAt":"1777611338227"} -->
The absolute value of the determinant can be thought of as a measure of how much multiplication by the matrix expands or contracts space.

[Page 68](xandria://reader/annotation?readableId=read_bd14be72-ff6a-4feb-afdf-3f6d7a8aedaf&annotationId=ann_d2463093-7d07-426c-952a-2a6179bd3de8)
<!-- xandria:highlight:end -->