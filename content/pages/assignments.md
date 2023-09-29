---
content_type: page
description: Problem sets and supporting files with notes.
learning_resource_types:
- Assignments
ocw_type: CourseSection
title: Assignments
uid: 7895813f-4f2b-7bfb-615c-c2281abd3e65
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Notes about Problem Sets 6 and 8
--------------------------------

In problem sets 6 and 8, students write MATLAB® programs to solve two-dimensional boundary integral equations based on Green's Theorem. In problem set 8, the inviscid streaming flow about an arbitrary two-dimensional object is calculated. The solution is done for a circular cylinder.

In problem set 8, the method is extended to the flow around a lift-generating airfoil with a wake across which there is a jump in the velocity potential. The two-dimensional Green function that is used is G = -ln r, where r is the distance between a "source point" and a "field point".

The student is not expected to write an efficient MATLAB® m-file for computing the integral of the Green Function over a panel. Rather, that m-file is given to the students and it is called **rank2d.m**. This m-file computes the integral of the Green function, g, and of the normal derivative of the Green function, **dg/dn**, over a panel. This m-function works in local coordinates for which the "source panel" is approximated as a line on a local x-axis with the center of the line at the local origin. The "field point" is at (x,y) in local coordinates. The normal vector to the panel is in the positive local y-direction.

To use **rank2d.m** function, the panel length and the location of the field point in local coordinates must first be determined. This is done in the m-function "**localize.m**", which should also be provided to the student who writes and used the remainder of the set of programs needed to complete the problem sets.

The m-functions, **rank2d** and **localize** are provided with problem set 6.

Problem Sets
------------

*   Problem Set 1 ({{% resource_link 11542d97-e377-9454-bc90-1df3cf8c14ce "PDF" %}})
*   Problem Set 2 ({{% resource_link 4c72a0f8-4ec3-703f-4ea3-66bf8a89f378 "PDF" %}})
*   Problem Set 3 ({{% resource_link 3dbd995a-3efa-ec42-35e0-bfdf570211f1 "PDF" %}})
*   Problem Set 4 ({{% resource_link c7df6c57-aeae-3acd-764e-bf9c0dd4e3fb "PDF" %}})
*   Problem Set 5 ({{% resource_link 63b7908c-80d0-e40c-27a0-e17795ea977c "PDF" %}})
*   Problem Set 6 ({{% resource_link 2a0d7c64-3e1b-76a4-6aa6-870c45cb9ede "PDF" %}})
*   Problem Set 7 ({{% resource_link 67e3905f-141f-4668-55a9-2904bf65a7d1 "PDF" %}})
*   Problem Set 8 ({{% resource_link 4deea7bd-6d76-74e2-8bae-2c469d3e9cf4 "PDF" %}})
*   Problem Set 9 ({{% resource_link d453d73b-8217-6c20-5d47-6c72d94249f8 "PDF" %}})
*   Problem Set 10 ({{% resource_link 4082f473-472b-53a4-e398-af14ae4ec07f "PDF" %}})

Supporting Files
----------------

*   64a012.fin ({{% resource_link a754e175-7355-6780-b2b6-88663a033701 "FIN" %}})
*   LOCALIZE.M ({{% resource_link 3e1bc3be-1447-ab58-cf2f-131676abc97f "M" %}})
*   RANK2D.M ({{% resource_link b2b6d935-1912-6925-fe8e-debf1e6c8b80 "M" %}})
*   wig4125.out ({{% resource_link ff168fc9-958e-0fa7-1df9-6ca4115ff2da "OUT" %}})
*   wigley5.out ({{% resource_link 49794f02-7590-5bed-8615-f698e47a26db "OUT" %}})
*   wigley9.out ({{% resource_link 3f430092-ba58-2f4a-2cfc-81c53ae9f09b "OUT" %}})