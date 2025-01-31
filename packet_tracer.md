---
layout: default
---

# SOHO-to-Enterprise Network Simulation using Cisco Packet Tracer

In this project, I utilized Cisco's free Packet Tracer program to simulate a network as it grew from a small, SOHO network to a fully-functional enterprise level network with multiple office buildings capable of seemless communication.

The overall goal was to demonstrate my ability to build, maintain, and add resources to a network infrastructure. Therefore, I developed a series of goals I would achieve in succession with each objective adding more complexity to the system. By the end, I would have essentially created a WAN for a simulated business.

My goals were, as follows:

## Goal 1: Create and secure a small SOHO network

## Goal 2: Create a small business network

## Goal 3: Create a decentralized office network

## Goal 4: Secure and centralize and office network

## Goal 5: Create a second secure, centralized office network with IoT devices

## Goal 6: Facilitate communication between the two office networks

## Goal 7: Ensure network is scalable for future expansion

Now, let's begin.

# Goal 1: Create a small SOHO network

After downloading and installing Packet Tracer, my first goal was to create a small SOHO network fit for a single business owner.

I created the home physical space and added the first workstation, calling it "CEO's Personal PC". Then, I added a laptop named "CEO's Laptop". Both were wired to a switch and given static IP addresses. A simple ping test was able to confirm both workstations could communicate!

The next step was to add the CEO's mobile phone to the network. To do this, I added a router capable of wireless communication. They wirelessly connected immediately and, since DHCP was configured on the router, the mobile phone automatically obtained an IP address!

However, the phone was not able to communicate with the PC or laptop.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
