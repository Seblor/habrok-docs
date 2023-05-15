---
description: /set-reward command
---

# 🛫 Setting a reward

## Permission

This command is available to Administrators only.

## Purpose

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

This commands allows you to set a reward to users whose reputation exceed a certain score.

## Arguments

### role

This is the role that will be set to the community member.

### score-needed

The score that the user needs to earn the role.

{% hint style="danger" %}
To avoid abuse, you cannot set a reward to a negative score. The bot is not intented to be used as an automoderator.
{% endhint %}

### score-before-rescind

This is the score under which the role will be removed. This is used as a buffer to avoid a role being added to and removed from a member too quickly.

{% hint style="warning" %}
The "score-before-rescind" must be lower than or equal to "score-needed".
{% endhint %}

{% hint style="info" %}
Since a role can only be rewarded once, you can edit a reward by running the command a second time with the same role.
{% endhint %}

## Example

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>
