---
type: PostLayout
title: Firewalls | Intrusion Detection Systems (IDS)  ⌨️
colors: colors-a
date: '2024-10-15'
author: content/data/team/doris-soto.json
excerpt: More context that may or may not be helpful
featuredImage:
  type: ImageBlock
  url: /images/featured-Image1.jpg
  altText: Post thumbnail image
backgroundImage:
  type: BackgroundImage
  url: /images/gallery-3.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 20
bottomSections:
  - elementId: ''
    type: RecentPostsSection
    colors: colors-f
    variant: variant-d
    subtitle: Recent posts
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 2
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    showFeaturedImage: true
    showReadMoreLink: true
  - type: ContactSection
    backgroundSize: full
    title: Stay up-to-date with my words ✍️
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
This week, I focused on **Operational Security**, specifically learning about **Firewalls** and **Intrusion Detection Systems (IDS)**, as discussed in sections 8.9-8.10, pages 667-670 of the course materials.

### Firewalls

Firewalls play a crucial role in securing computer networks by controlling the flow of traffic between an internal network and external sources. They enforce security policies by blocking or allowing specific types of traffic based on a set of predefined rules. I learned that there are different types of firewalls, including **packet-filtering firewalls**, **stateful firewalls**, and **application-layer firewalls**. Each type offers a different level of control and inspection of traffic. The ability of firewalls to inspect packets and monitor the state of connections ensures that only legitimate traffic is allowed, thereby protecting the network from unauthorized access.

One key takeaway was that while firewalls are critical to network security, they alone are not enough to fully secure a network. A well-rounded security approach must include other tools and techniques to protect against modern threats, as firewalls primarily focus on preventing unauthorized external access.

### Intrusion Detection Systems (IDS)

In addition to firewalls, I learned about **Intrusion Detection Systems (IDS)**, which complement firewalls by monitoring network traffic for suspicious behavior. IDSs can detect anomalies and potential threats, like attempted breaches or unauthorized activity within the network. They do this by comparing network activity against a database of known attack signatures (signature-based detection) or by identifying deviations from normal patterns of behavior (anomaly-based detection).

An important distinction is that while firewalls are preventive tools, IDSs are **detective** tools. IDSs don't prevent attacks but alert network administrators to potential threats. Some systems, known as **Intrusion Prevention Systems (IPS)**, take it a step further by actively blocking detected threats.

### Reflection

This week's content emphasized that securing a network is a multi-layered process. Firewalls provide a strong first line of defense, but they must be paired with tools like IDS to detect more sophisticated or internal threats. I found it fascinating to understand how these technologies work together to provide a secure network environment.

This module has made me more aware of the limitations of each security tool and the importance of using them in conjunction with one another to create a robust security posture. It also reinforced the idea that constant monitoring and updating of security systems are essential in keeping networks safe from evolving threats.
