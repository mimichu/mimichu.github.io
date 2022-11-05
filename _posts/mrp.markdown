---
layout: post
title:  "Deep Projective Rotation Estimation through Relative Supervision"
date:   2022-11-15 22:21:59 +00:00
image: /images/mrp.jif
categories: research
author: "Chuer Pan"
authors: "Brian Okorn*, <strong>Chuer Pan*</strong>, Martial Herbert, David Held"
venue: "Conference on Robot Learning (CoRL)"
paper: https://openreview.net/pdf?id=Z1Kg3RNv3M5
website: https://sites.google.com/view/deep-projective-rotation/home
Open Review: https://openreview.net/forum?id=ZezSmJq06Ep
---
We propose a new algorithm for self-supervised orientation estimation which utilizes Modified Rodrigues Parameters to stereographically project the closed manifold of SO(3) to the open manifold of 3D Euclidean space, which avoids the local optima common when naively applying relative self-supervision for object orientation estimation, allowing for faster convergence.