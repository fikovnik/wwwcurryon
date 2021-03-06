---
layout: 2017-abstract
title: "Haskell SpriteKit — A Case Study in Turning a Stateful into a Purely Functional API"
by: Manuel Chakravarty
affiliation: UNSW Australia &amp; Applicative
profpic-class: manuel_chakravarty
---

[@TacticalGrace](https://twitter.com/TacticalGrace)

<br/>

### Abstract

Graphics, animation, and games programming in Haskell faces a dilemma. We can either use existing frameworks with their highly imperative APIs (such as OpenGL, Cocos2D, or SpriteKit) or we waste a lot of energy trying to re-engineer those rather complex systems from scratch. Or, maybe, we can escape the dilemma. Instead of a Haskell program directly manipulating the mutable object-graph of existing high-level frameworks, we provide an API for purely functional transformations of a Haskell data structure, together with an adaptation layer that transcribes those transformations into edits of the mutable object-graph. I this talk, I will explain how I used this approach to architect a Haskell binding to the animation system and physics engine of Apple’s SpriteKit framework. I will discuss both how the binding is structured internally and how it achieves the translation of Haskell side changes to SpriteKit and vice versa, such that it is sufficiently efficient. Moreover, I will explain how to use the Haskell library to implement animations and games. I will use Haskell and SpriteKit as concrete technology in all examples, but it requires neither previous experience with Haskell nor with SpriteKit. In a similar vain, the talk is based on Apple’s SpriteKit framework, as there is no reasonable (in terms of effort) way around platform-specific technology if you want something that is simultaneously state-of-the-art, practically useful, and convenient to use. Nevertheless, the concepts explained in the talk transcend the specific technology and are generally applicable. Moreover, the entire code base of the Haskell binding is open source and available from https://github.com/mchakravarty/HaskellSpriteKit

### Bio

Manuel M T Chakravarty is an Associate Professor at UNSW Australia and the indie developer behind the interactive development environment Haskell for Mac — one of the first Swift apps on the Mac App Store. His core research interests are functional programming, novel compiler technology, and high-performance computing. He contributed to both the design and implementation of the Haskell programming language as well as several Haskell tools and open source libraries, including multiple systems for data parallel programming of multicore CPUs and GPUs. Over the last two years, he has focused on making functional programming more broadly accessible and on exploring its role in app development in Swift. Most importantly, he believes in the fruitful combination of theory and practice.

