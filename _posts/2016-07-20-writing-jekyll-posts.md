---
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true
---

# Test Article from Ars --> https://arstechnica.com/cars/2022/02/this-ai-mechanic-scans-your-car-or-tires-to-diagnose-defects/

# Markddown

### UVeye

Can you train an AI to take a breath, wince, and remark, "Well, it's going to cost you"?

That's probably easier than teaching one to diagnose problems with your car after a visual scan of its undercarriage, and yet the latter is what an Israeli company called UVeye has done. The company has developed what you might think of as a car scanner that can diagnose problems in just a few seconds. Drive past it, and it will image your car's panels, tires, or underbody, spotting dings, oil leaks, foreign objects, or other problems, flagging them for remedy.

It's another intriguing example of the civilian spinoffs that have emerged from Israel's national security sector over the last couple of decades as sensors and algorithms find new life on civvy streets.

"Originally, what we did was utilize artificial intelligence to look for security threats or illicit materials below vehicles and access control points. We were the first company in the world to do it on the first go without ever seeing a vehicle before. And we developed a unique algorithm that is model- and make-agnostic," Yaron Saghiv, UVeye's head of communications, told Ars.

The decision to expand beyond the national security sector came about three years ago. "We were installed in over 100 sensitive sites in the world—seaports, airports, prisons—but around three years ago, we definitely understood that there is a much bigger market that could utilize this, which is the automotive market," Saghiv said.

UVeye has developed a trio of solutions that leverage the technology. One, called Artemis, inspects tires, using OCR to detect which brand, size, and DOT rating is marked on the tire. It calculates the wear and tear of the tread and sidewalls and even checks the tire's current pressure.

Another, called Helios, is an undercarriage scanner for mechanical faults. As the car drives over the scanner, the software constructs a 3D model of its underside, flagging anything unexpected like an oil stain or bent exhaust or suspension component.

Both Artemis and Helios seem obviously useful to fleet managers and repair shops, and it's probably unsurprising that the used car retailer Carmax has invested in the company.

However, **UVeye** has designs on the whole automotive supply chain. And its Atlas system is aimed more at OEMs during the manufacturing stage. Atlas performs a 360-degree scan of the entire vehicle as it moves down the line, detecting defects at even the millimeter range.

Volvo, Toyota, and Hyundai evidently like the concept. All three OEMs have invested in UVeye, with the Japanese and Swedish automakers having begun using its technology on their assembly lines.