---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: さまよう旅人のためのウェブマガジン
      color: text-dark
      type: TitleBlock
    subtitle: RooLone Magazine
    text: |
      旅人サークルの "Plainbox" のウェブマガジン「RooLone Magazine」です。
      さまよう旅人によるさまよう旅人に向けた情報をローペースながらも発信する予定です。
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: See Tutorials
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-neutral-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: >-
    http://res.cloudinary.com/dikcsjqfo/image/upload/v1722087548/RooLone/Thumb/logo_main.jpg
  type: Seo
type: PageLayout
isDraft: false
---
