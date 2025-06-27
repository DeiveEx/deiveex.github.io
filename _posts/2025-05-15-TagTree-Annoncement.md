---
title: "TagTree: An hierarchical Tag System for Unity"
date: 2025-05-15 13:00:00-0000
categories: announcement my-tools development tools
header:
    overlay_color: "#333"
    actions:
      - label: "Unity Asset Store"
        url: "https://assetstore.unity.com/packages/tools/utilities/tagtree-319017"
show_overlay_excerpt: true
excerpt: Tired of all the limitations of Unity Tags? Try my tool/extension for better Unity tags!
---

Hello again!

This time I'm here to announce a tool/extension I've created to help me develop my games in Unity. It's called **[TagTree](https://assetstore.unity.com/packages/tools/utilities/tagtree-319017)**, and it's a better way to use tags in Unity. It takes a lot of inspiration from Unreal's *GameplayTags*, although there's some changes based on my preference.

<p align="center">
    <a href="https://assetstore.unity.com/packages/tools/utilities/tagtree-319017">
        <img src="/assets/images/TagTree/Icon.jpg">
    </a>
</p>

Tags in TagTree are defined in a tree-like structure, and you can check if an object has a tag on any level of the tree, meaning that if a character has a tag **"State.Stunned.Electric"** and you want to check if the character is stunned, you can simply check for **"State.Stunned"** instead.

Basically anything can have tags, you just need to create an object of type *TagContainer*, but there's already a built-in extension specifically for GameObjects, so you can just use that straight away!

Here's some more details/features:

- **Tree-like Tag structure:** Tags uses the standard parent.child.grandchild, and you can have as many levels and as many children Tags as you want!
- **Tag Stacking:** Applying the same Tag multiple times to the same object increases its stack counter, and you can can use this value in your game however you like!
- **Tag Queries:** Want to know if an object has a specific combination of Tags? TagQueries are a flexible and powerful solution!
- **Built-In GameObject extension:** While anything can have Tags, the package includes some helper methods to add and search for GameObjects with specific tags!
- **Performant:** Tags are only created once and comparisions are basically integer comparisions! TagContainers are nothing more than a dictionary, so lookups are as fast as it can be!
- **Included Tag Editor and Inspector field:** Use an easy to use Editor window to create your Tags, and easily select created Tags from the inspector using a searchable dropdown!
- **Multiple Tag Files:** Having a tree-like structure is not enough for you to organize your Tags? Don't worry, you can separate them into multiple files!

The tool is already pretty complete and easy to use, but there's a couple of things I'd still like to do sometime, like:
- Native inspector integration: right now if you wanna add tags to a GameObject you need to either do it through code or use the included helper MonoBehavior (*TagTreeComponent*). I've seen some assets on the Asset Store add special fields right at the top of the inspector, below the GameObject's name. Using this space to define tags would be useful instead of relying on a component.
- Generate C# scripts for Tags: right now you can create a field of type *TagReference* and a custom dropdown will appear in the inspector for you to choose your tag. But if for some reason you don't want to use the inspector to choose Tags, your only other choice is to use their string name. It would be nice to generate a C# script with constants for each tag.

If that picked your interested, [click here to check it out!](https://assetstore.unity.com/packages/tools/utilities/tagtree-319017)
{: .notice--info}