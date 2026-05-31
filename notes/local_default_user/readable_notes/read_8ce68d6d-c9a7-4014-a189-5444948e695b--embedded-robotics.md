# 14 Localization and Navigation

## 14.1 Localization

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_13616e0e-7350-4b43-bb5c-5128363be30d","sourceUpdatedAt":"1777610627913"} -->
, today probabilistic methods that minimize uncertainty are applied to the whole problem complex at once, especially simultaneous localization and mapping \(SLAM\).

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_13616e0e-7350-4b43-bb5c-5128363be30d)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_ab46520b-d7be-4334-b241-374fbfa891b9","sourceUpdatedAt":"1777610627913"} -->
DistBug

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_ab46520b-d7be-4334-b241-374fbfa891b9)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_d24b1453-d68b-4f7b-81ce-c0789bd72372","sourceUpdatedAt":"1777610627913"} -->
used in a continuously changing environment or

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_d24b1453-d68b-4f7b-81ce-c0789bd72372)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_d7512199-9287-4cbb-9ad0-36f0547c8aba","sourceUpdatedAt":"1777610627913"} -->
path

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_d7512199-9287-4cbb-9ad0-36f0547c8aba)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_1c4bb4f3-ad60-4271-89ca-2a1026347374","sourceUpdatedAt":"1777610627913"} -->
not necessarily have to be optimal.

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_1c4bb4f3-ad60-4271-89ca-2a1026347374)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_a750deaa-c215-4711-a3e0-f73b58b989cd","sourceUpdatedAt":"1777610627913"} -->
Dijkstra or A\*

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_a750deaa-c215-4711-a3e0-f73b58b989cd)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_99f3507c-076b-4c91-9848-a985baf5fdbf","sourceUpdatedAt":"1777610627913"} -->
e shortest path offline

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_99f3507c-076b-4c91-9848-a985baf5fdbf)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_68c05dbc-88de-47d6-b400-e5a4eb283c67","sourceUpdatedAt":"1777610627913"} -->
perate in direct interaction with the robot’s sensors while driving.

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_68c05dbc-88de-47d6-b400-e5a4eb283c67)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_f18af617-bebe-4a40-a385-df36cea0e205","sourceUpdatedAt":"1777610627913"} -->
e Quadtree method.

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_f18af617-bebe-4a40-a385-df36cea0e205)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_3b64911e-d099-4eb2-a05a-ac7fb80af320","sourceUpdatedAt":"1777610627913"} -->
central problems for driving robots is localization.

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_3b64911e-d099-4eb2-a05a-ac7fb80af320)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_a32c69aa-edea-4b62-b6c1-6e0109b1e1a7","sourceUpdatedAt":"1777610627913"} -->
. For many application scenarios, we need to know a robot’s position and orientation \(pose\) at all times.

[Page 274](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_a32c69aa-edea-4b62-b6c1-6e0109b1e1a7)
<!-- xandria:highlight:end -->

## 14.1.1 Radio Beacons

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_715976da-0d03-43e1-9efd-7bbcf6a9ddf5","sourceUpdatedAt":"1777610627913"} -->
without local sensors, three beacons are required.

[Page 275](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_715976da-0d03-43e1-9efd-7bbcf6a9ddf5)
<!-- xandria:highlight:end -->

## 14.1.2 Light Beacons

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_9fdc367a-5b8b-4d32-a8ba-7c4036619a90","sourceUpdatedAt":"1777610627913"} -->
Only the robot’s position

[Page 276](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_9fdc367a-5b8b-4d32-a8ba-7c4036619a90)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_102b80ac-4410-469a-90da-ea9dc70fc784","sourceUpdatedAt":"1777610627913"} -->
not its orientation.

[Page 276](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_102b80ac-4410-469a-90da-ea9dc70fc784)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_5ed1c464-10c4-47b5-87ca-6b9568713167","sourceUpdatedAt":"1777610627913"} -->
GNSS,

[Page 276](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_5ed1c464-10c4-47b5-87ca-6b9568713167)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_f239599c-d08d-49e0-8133-6f4432b5a789","sourceUpdatedAt":"1777610627913"} -->
additional compass sensor.

[Page 276](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_f239599c-d08d-49e0-8133-6f4432b5a789)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_2fbf997b-8455-43d9-bf83-524d2805e594","sourceUpdatedAt":"1777610627913"} -->
autonomous robot with local sensors.

[Page 276](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_2fbf997b-8455-43d9-bf83-524d2805e594)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_8d794ff7-a2bd-4679-8599-8f1d3cd183c1","sourceUpdatedAt":"1777610627913"} -->
omni-directional vision system t

[Page 276](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_8d794ff7-a2bd-4679-8599-8f1d3cd183c1)
<!-- xandria:highlight:end -->

## 14.1.3 Dead Reckoning

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_db6c04e9-53b0-4a60-9779-b2cfd1809150","sourceUpdatedAt":"1777610627913"} -->
rely on their wheel encoders alone for short-term localization

[Page 277](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_db6c04e9-53b0-4a60-9779-b2cfd1809150)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_02cc0b7c-cace-4f36-9724-d9dfa7bf9743","sourceUpdatedAt":"1777610627913"} -->
dead reckoning

[Page 277](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_02cc0b7c-cace-4f36-9724-d9dfa7bf9743)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_b123bcf1-ab95-4fad-8f83-557f42920d38","sourceUpdatedAt":"1777610627913"} -->
vector-adding their course segments to establish their current position.

[Page 277](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_b123bcf1-ab95-4fad-8f83-557f42920d38)
<!-- xandria:highlight:end -->

## 14.2 Environment Representation

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_b1bfc48b-52fa-4d48-b7bf-0871587dbbf5","sourceUpdatedAt":"1777610627913"} -->
n on-board compass is very valuable in the absence of global sensors.

[Page 278](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_b1bfc48b-52fa-4d48-b7bf-0871587dbbf5)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_3cabd502-b271-4b29-889a-9e293f0b4bfd","sourceUpdatedAt":"1777610627913"} -->
s local coordinate system.

[Page 278](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_3cabd502-b271-4b29-889a-9e293f0b4bfd)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_e7553d7c-80d3-49c8-989d-42ea05a6cd1f","sourceUpdatedAt":"1777610627913"} -->
establish a map \(

[Page 278](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_e7553d7c-80d3-49c8-989d-42ea05a6cd1f)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_e5868515-f8b6-4558-9ffb-c5707592dacb","sourceUpdatedAt":"1777610627913"} -->
plan a path

[Page 278](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_e5868515-f8b6-4558-9ffb-c5707592dacb)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_397b2653-87a1-42cf-b01a-5faec8b103d7","sourceUpdatedAt":"1777610627913"} -->
global or world coordinates.

[Page 278](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_397b2653-87a1-42cf-b01a-5faec8b103d7)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_e14ea200-29db-4cbd-8e2a-d44bda92c4c0","sourceUpdatedAt":"1777610627913"} -->
homogeneous coordinates.

[Page 279](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_e14ea200-29db-4cbd-8e2a-d44bda92c4c0)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_1c19cd6a-47d0-403c-bc73-4728f16c9ac2","sourceUpdatedAt":"1777610627913"} -->
arbitrary long 3D transformation sequences can be summarized in a single 4  4 matrix \(se

[Page 279](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_1c19cd6a-47d0-403c-bc73-4728f16c9ac2)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_19bca6a1-c303-4e5b-a3ac-9dd4a6222b35","sourceUpdatedAt":"1777610627913"} -->
Configuration Space and Occupancy Grid.

[Page 280](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_19bca6a1-c303-4e5b-a3ac-9dd4a6222b35)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_83f102d4-3a78-4027-b1f7-67ab43d4193e","sourceUpdatedAt":"1777610627913"} -->
In configuration space, we are given the dimensions of the environment plus the coordinates of all obstacles, e.g., walls, represented by line segments. In an occupancy grid, the environment is specified at a certain resolution with individual pixels either representing free space \(white pixels\) or an obstacle \(black pixels\).

[Page 280](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_83f102d4-3a78-4027-b1f7-67ab43d4193e)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_f5f43b55-675f-4308-80be-9271fbaabd89","sourceUpdatedAt":"1777610627913"} -->
ijkstra and A\*, require a distance graph as input

[Page 280](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_f5f43b55-675f-4308-80be-9271fbaabd89)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_61704859-e14e-4947-ab76-a72c5e199542","sourceUpdatedAt":"1777610627913"} -->
A distance graph is an environment description at a higher level.

[Page 280](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_61704859-e14e-4947-ab76-a72c5e199542)
<!-- xandria:highlight:end -->

## 14.3 Quadtree

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_92698cb0-f96b-4d6d-9521-46cfa11cddad","sourceUpdatedAt":"1777610627913"} -->
e number of nodes in the resulting distance graph will be huge,

[Page 281](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_92698cb0-f96b-4d6d-9521-46cfa11cddad)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_df5b5cc4-558f-4f37-8d67-a3ab599dc630","sourceUpdatedAt":"1777610627913"} -->
path planning in such a graph will result in suboptimal paths,

[Page 281](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_df5b5cc4-558f-4f37-8d67-a3ab599dc630)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_834c8dc4-03cd-461e-ab0d-aba5a8e62f49","sourceUpdatedAt":"1777610627913"} -->
a leaf.

[Page 281](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_834c8dc4-03cd-461e-ab0d-aba5a8e62f49)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_f40b0188-7090-4f90-b6d2-00f1437797de","sourceUpdatedAt":"1777610627913"} -->
distance graph.

[Page 282](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_f40b0188-7090-4f90-b6d2-00f1437797de)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_05e7381d-1cbe-42a3-a6a8-e7624c5a2982","sourceUpdatedAt":"1777610627913"} -->
e final path planning st

[Page 282](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_05e7381d-1cbe-42a3-a6a8-e7624c5a2982)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_e1a16f94-2627-43a4-8768-2f0a8a7c966d","sourceUpdatedAt":"1777610627913"} -->
A\* algorithm on the distance graph.

[Page 282](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_e1a16f94-2627-43a4-8768-2f0a8a7c966d)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_e2ddcd47-f52a-455b-9ba4-b6df22208106","sourceUpdatedAt":"1777610627913"} -->
square area with the size being a power of two,

[Page 282](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_e2ddcd47-f52a-455b-9ba4-b6df22208106)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_578090e0-6e09-488e-a4c1-08902b47a864","sourceUpdatedAt":"1777610627913"} -->
Liang-Barsky algorithm,

[Page 284](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_578090e0-6e09-488e-a4c1-08902b47a864)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_6c848482-fe9f-4344-81dc-c44f3913d6b6","sourceUpdatedAt":"1777610627913"} -->
Cohen-Sutherland algorithm,

[Page 284](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_6c848482-fe9f-4344-81dc-c44f3913d6b6)
<!-- xandria:highlight:end -->

## 14.4 Visibility Graph

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_fa659229-e25f-414e-bdb6-a6b5eedc4b87","sourceUpdatedAt":"1777610627913"} -->
visibility graph method uses corner points of obstacles instead.

[Page 285](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_fa659229-e25f-414e-bdb6-a6b5eedc4b87)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_5f6246e8-5f41-491f-86a9-7f9997185193","sourceUpdatedAt":"1777610627913"} -->
environment is represented as a configuration space,

[Page 285](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_5f6246e8-5f41-491f-86a9-7f9997185193)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_527de361-d013-4bcc-b055-5c56de095ad0","sourceUpdatedAt":"1777610627913"} -->
One problem of this approach is that it allows lines to pass very closely to an obstacle, so this would only work for a theoretical robot with a zero diameter.

[Page 285](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_527de361-d013-4bcc-b055-5c56de095ad0)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_85570069-bdc8-4c7d-ae7f-6b56edfa3f48","sourceUpdatedAt":"1777610627913"} -->
this problem can be easily solved by virtually enlarging each obstacle by half of the robot’s diameter before applying the algorithm

[Page 285](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_85570069-bdc8-4c7d-ae7f-6b56edfa3f48)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_f3396fe6-ea85-44ce-9d26-906e6e59a3d2","sourceUpdatedAt":"1777610627913"} -->
robot’s orientation for driving,

[Page 286](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_f3396fe6-ea85-44ce-9d26-906e6e59a3d2)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_58b2b916-214d-46cf-b409-3d242a87ad4a","sourceUpdatedAt":"1777610627913"} -->
piano mover’s problem

[Page 286](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_58b2b916-214d-46cf-b409-3d242a87ad4a)
<!-- xandria:highlight:end -->

## 14.5.1 Delaunay Triangulation

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_06220e57-3ceb-4662-bc38-dc8e0fd4e197","sourceUpdatedAt":"1777610627913"} -->
If we have a Voronoi diagram, we can use the end points of all Voronoi lines as nodes to construct the distance graph.

[Page 288](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_06220e57-3ceb-4662-bc38-dc8e0fd4e197)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_e37d6534-ef92-44e1-a8e5-9f5e65829403","sourceUpdatedAt":"1777610627913"} -->
Delaunay triangulation tries to construct a Voronoi diagram with much less computational effort.

[Page 288](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_e37d6534-ef92-44e1-a8e5-9f5e65829403)
<!-- xandria:highlight:end -->

## 14.6 Potential Field Method

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_27168288-087d-4102-b468-985fd94fa7fc","sourceUpdatedAt":"1777610627913"} -->
The robot can get stuck in local minima.

[Page 291](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_27168288-087d-4102-b468-985fd94fa7fc)
<!-- xandria:highlight:end -->

## 14.7 Wandering Standpoint Algorithm

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_024e036f-5b14-4318-986f-40db0e886829","sourceUpdatedAt":"1777610627913"} -->
n Local path planning algorithm.

[Page 292](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_024e036f-5b14-4318-986f-40db0e886829)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_2d79cfbb-ac4a-4404-a007-9415468c611c","sourceUpdatedAt":"1777610627913"} -->
Local distance sensor.

[Page 292](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_2d79cfbb-ac4a-4404-a007-9415468c611c)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_61a252de-e7a4-4e6b-b195-bc134f4f2ce9","sourceUpdatedAt":"1777610627913"} -->
The algorithm can lead to an endless loop for extreme obstacle placements. In this case, the robot keeps driving, but never reaches the goal.

[Page 292](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_61a252de-e7a4-4e6b-b195-bc134f4f2ce9)
<!-- xandria:highlight:end -->

## 14.8 Bug Algorithm Family

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_fed12f66-9d23-4513-a9db-6213d67d397c","sourceUpdatedAt":"1777610627913"} -->
Local planning algorithm that guarantees convergence and will find a path if one exists or report that goal is unreachable.

[Page 293](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_fed12f66-9d23-4513-a9db-6213d67d397c)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_4f72d847-71aa-4185-87ca-e45eec2dcd68","sourceUpdatedAt":"1777610627913"} -->
nice theoretical properties, it is not very usable in practice, as the positioning accuracy and sensor distance required for the success of the algorithm are usually not achievable.

[Page 294](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_4f72d847-71aa-4185-87ca-e45eec2dcd68)
<!-- xandria:highlight:end -->

## 14.9 Dijkstra’s Algorithm

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_ce54a894-81ab-4c6e-b48e-8039462c0f76","sourceUpdatedAt":"1777610627913"} -->
distances \(non-negative\)

[Page 297](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_ce54a894-81ab-4c6e-b48e-8039462c0f76)
<!-- xandria:highlight:end -->

## 14.10 A\* Algorithm

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_29accd6d-fce1-4352-8928-bbf59ff30595","sourceUpdatedAt":"1777610627913"} -->
O\(klogkv\) f

[Page 300](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_29accd6d-fce1-4352-8928-bbf59ff30595)
<!-- xandria:highlight:end -->

## 14.11 Probabilistic Localization

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_3c9bb4b5-7fa2-448e-a6c4-02c0b01ba77b","sourceUpdatedAt":"1777610627913"} -->
The aim of probabilistic localization is to provide the best possible estimate of the robot’s current configuration based on all previous data and their associated distribution functions.

[Page 302](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_3c9bb4b5-7fa2-448e-a6c4-02c0b01ba77b)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_74015baf-06ed-4301-b32d-d5d917893a9b","sourceUpdatedAt":"1777610627913"} -->
probability mass function \(PMF\),

[Page 302](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_74015baf-06ed-4301-b32d-d5d917893a9b)
<!-- xandria:highlight:end -->

## 14.12 SLAM

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_5d44ac53-002a-423b-8074-eaec4c50a6c8","sourceUpdatedAt":"1777610627913"} -->
The most successful method for solving this problem is a statistical method called simultaneous localization and mapping, or SLAM

[Page 307](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_5d44ac53-002a-423b-8074-eaec4c50a6c8)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_a664902c-7e15-4d63-bf22-8b0fe6be4692","sourceUpdatedAt":"1777610627913"} -->
SLAM combines a Kalman filter with a particle filter to generate a robust map that can deal with sensor inaccuracies.

[Page 307](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_a664902c-7e15-4d63-bf22-8b0fe6be4692)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_febd2dd7-36c7-49f0-84e2-e7861bae495a","sourceUpdatedAt":"1777610627913"} -->
adverse effect of drift in positioning in the absence of SLAM.

[Page 307](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_febd2dd7-36c7-49f0-84e2-e7861bae495a)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_d3020682-1ef3-4c0b-ac73-1be5bed203f0","sourceUpdatedAt":"1777610627913"} -->
e perceived angles from odometry deviate too much f

[Page 307](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_d3020682-1ef3-4c0b-ac73-1be5bed203f0)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_bee6ac90-fc22-4324-9e34-1e9543dafed7","sourceUpdatedAt":"1777610627913"} -->
However, there are also implementations of SLAM outside of ROS, such as BreezySLAM from S. Levy,27

[Page 308](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_bee6ac90-fc22-4324-9e34-1e9543dafed7)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_1cfafd33-800e-4cde-af89-78e89cdfe752","sourceUpdatedAt":"1777610627913"} -->
tinySLAM

[Page 308](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_1cfafd33-800e-4cde-af89-78e89cdfe752)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_067008a8-a98d-4d5e-ad9c-9177589c7469","sourceUpdatedAt":"1777610627913"} -->
the algorithm does an update of its internal state by using the latest Lidar scan.

[Page 308](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_067008a8-a98d-4d5e-ad9c-9177589c7469)
<!-- xandria:highlight:end -->

<!-- xandria:highlight:start {"version":1,"sourceReadableId":"read_8ce68d6d-c9a7-4014-a189-5444948e695b","annotationId":"ann_1f8aed98-366e-48c7-b148-91fe16fb2dd6","sourceUpdatedAt":"1777610627913"} -->
ORB-SLAM2.3

[Page 308](xandria://reader/annotation?readableId=read_8ce68d6d-c9a7-4014-a189-5444948e695b&annotationId=ann_1f8aed98-366e-48c7-b148-91fe16fb2dd6)
<!-- xandria:highlight:end -->