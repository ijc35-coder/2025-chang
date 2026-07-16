---
layout: project
title: Monocoque Design and Manufacturing
description: Design, Manufacturing Process, and Integration of Monocoque
technologies: [Autodesk Inventor, Vault, MATLAB, ANSYS, Composite Manufacturing]
image: /assets/images/clearcoat.jpeg
---



As the monocoque subteam lead, I am currently responsible for the design, manufacturing, and integration of the monocoque, or composite frame of the vehicle, on Cornell FSAE Racing during the Fall 2025-Spring 2026 school year. I am also responsible for overlooking the design and manufacturing of the protective structures as a subteam lead. 

The monocoque is an intensive part that requires knowing the mounting locations, bolt size, and loading conditions of every other system that integrates with the car. This integration includes the suspension, ergonomics, aerodynamics, powertrain peripherals, accumulator, and low voltage subteams. There are over 60 individial parts that mount to the monocoque that I must be aware of as the designer. 

## Monocoque Design-to-Manufacturing Process

The design and manufacturing of the carbon-fiber monocoque followed a multi-stage workflow requiring close coordination between the torsionally stiff design, manufacturing constraints, and full multi-system level integration. As the sole monocoque designer, I owned the process from CAD through final layup and cure. Each step required careful time management and planning to ensure the monocoque completion date gave the team enough time to fully integrate each system with the monocoque and have three full months of drive days to test vehicle performance before competition in June.

### 1. CAD Design
Designed the new year's monocoque geometry, incorporating packaging constraints and flat mounting interfaces for all vehicle subsystems while eliminating unnecessary features to shave off as much weight as possible from the previous design.

<!-- Monocoque Geometry Changes -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/monocoquegeometrychange.png' | relative_url }}" alt="MonocoqueGeometryChanges">
  <figcaption>'25 and '26 monocoque overlaid ('26 is visible, '25 is transparent)</figcaption>
</figure>

<!-- Overall Timeline -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/timeline.jpeg' | relative_url }}" alt="Timeline">
  <figcaption>Preliminary Gantt Chart to Map Out Design and Manufacturing Process</figcaption>
</figure>

### 2. Plug Development
Collaborated with external manufacturers to route monocoque top and bottom plugs directly from created CAD models. Sourced high-density polyurethane foam for plug fabrication. Verified all mounting locations and bolt selections with over 30 part designers. Designed and printed custom 3D-printed jigs to accurately locate and fixture all mounting holes on the monocoque.

### 3. Plug Post-Processing
Performed extensive sanding and surface preparation on the top and bottom plugs, followed by Duratec coating to achieve a high-quality surface finish suitable for mold transfer.

<!-- Plug Post Processing and Jigging -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/jigs.png' | relative_url }}" alt="PlugandJigs">
  <figcaption>Top Plug with 3D-printed Jigs (Left), Bottom Plug with 3D-printed Jigs (Right)</figcaption>
</figure>

### 4. Ply Schedule Development & Material Testing
Developed laminate ply schedules for carbon-fiber skins and aluminum honeycomb cores. Fabricated and tested composite panels using three-point bend tests and perimeter shear tests to validate stiffness and strength of schedules.

<!-- Composite Layups to Manufacture Test Panels -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/testpanel.jpeg' | relative_url }}" alt="TestPanels">
  <figcaption>Vacuum-bagged Composite Test Panels (Carbon Fiber Skin with Aluminum Honeycomb Core)</figcaption>
</figure>

<!-- Three Point Bend Tests -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/threepoint.jpg' | relative_url }}" alt="ThreePointBend">
  <figcaption>Three Point Bend Tests with Equivalent Steel Tubes</figcaption>
</figure>

<!-- Perimeter Shear Tests -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/perimetershear.png' | relative_url }}" alt="Perimetershear">
  <figcaption>Perimeter Shear Tests with Test Panels</figcaption>
</figure>

### 5. Mold Fabrication
Manufactured the top and bottom monocoque molds through two wet layup processes. Post-processed molds to ensure a smooth, defect-free surface capable of producing consistent, high-quality composite parts.

<!--Top Mold Wet Layup -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/wetlayup.png' | relative_url }}" alt="Wetlayup">
  <figcaption>Creating the Top Plug by Wet Layup Using Vinyl Ester Resin, Carbon Fiber, and Fiberglass</figcaption>
</figure>

<!--Completed Top and Bottom Mold-->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/mold.jpeg' | relative_url }}" alt="Molds">
  <figcaption>Top and Bottom Molds Set Up Together</figcaption>
</figure>

### 6. Monocoque Manufacturing
Over a ten-day intensive manufacturing period, completed carbon-fiber and aluminum honeycomb layups and vacuum bagging operations using the completed molds, resulting in a torsionally stiff, reliable monocoque ready for vehicle integration and testing.

The accelerated schedule allowed accelerated vehicle integration. Completing the monocoque early supported a February 2 drive-date target and provided approximately five months for integration, reliability testing, tuning, and driver development before competition.

Manufacturing included:

- Manufacturing and post-processing composite top and bottom mold
- Cutting and organizing all prepreg plies
- Laying up 16 layers of prepreg (largest ply schedule was 8-core-8)
- Fitting and splicing aluminum honeycomb core
- Vacuum bagging and curing
- Post-processing the cured monocoque

<!-- Laying Up Inside the Monocoque -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/molayup.JPG' | relative_url }}" alt="MonocoqueLayup">
  <figcaption>Inside the Monocoque and Molds, Laying Up the Monocoque</figcaption>
</figure>

<!-- Aluminum Honeycomb Core -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/core.jpeg' | relative_url }}" alt="Core">
  <figcaption>Rear of Monocoque Aluminum Honeycomb Core with Carbon Fiber Pucks and Core Splice</figcaption>
</figure>

<!-- Completed Monocoque Directly After Final Cure -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/monocoque.JPG' | relative_url }}" alt="Monocoque">
  <figcaption>Team that Assisted with Manufacturing Monocoque After Successful Final Cure</figcaption>
</figure>

<!-- Clear Coating the Monocoque -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/clearcoat.jpeg' | relative_url }}" alt="Clearcoat">
  <figcaption>Clear Coated Monocoque After Release</figcaption>
</figure>

<!-- Manufacturing Timeline -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/layuptimeline.png' | relative_url }}" alt="timeline">
  <figcaption>Full monocoque manufacturing schedule during January Manufacturing Period</figcaption>
</figure>

### 7. Monocoque Torsional-Stiffness

Rather than choosing an arbitrary torsional stiffness goal, the vehicle was modeled as a set of rotational springs in series. The model included the effective wheel stiffness, suspension-structure stiffness, and monocoque stiffness:

## Torsional Stiffness Target Development

The integrated monocoque was mounted to the welding table, where the rear corners were rigidly bolted to the table to apply an "infinitely stiff" boundary condition. A known moment was applied to create a one-droop case using specific weight intervals, and angular deflection was measured with dial indicators.

<!-- Twist test Picture -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/fulltwisttest.png' | relative_url }}" alt="Torsional stiffness test">
  <figcaption>Overall Twist Test Set-up</figcaption>
</figure>

<!-- Twist test Picture zoomed-->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/twisttestzoom.png' | relative_url }}" alt="Torsional stiffness test rear corners">
  <figcaption>Rear Corner Twist Test Set-up</figcaption>
</figure>

<!-- Torsional Stiffness calc -->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/monocoquetorsion.png' | relative_url }}" alt="Torsional stiffness target calculation">
  <figcaption>Monocoque Torsional Stiffness Calculated from Twist Test</figcaption>
</figure>

<!-- Torsional Stiffness hubhub calc-->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/hubhub.png' | relative_url }}" alt="Torsional stiffness target calculation">
  <figcaption>Hub-to-Hub Torsional Stiffness Calculated from Twist Test</figcaption>
</figure>

From the measured load-deflection curves:

| Component | Measured Torsional Stiffness |
|-----------|----------------------------:|
| Monocoque | **3364 Nm/deg** |
| Hub-to-Hub Vehicle | **1907 Nm/deg** |

The hub-to-hub stiffness includes compliance from both the suspension and the monocoque.

---

## Calculating Suspension Stiffness

The suspension and chassis act as torsional springs in series, so

```
1 / K_hub = 1 / K_monocoque + 1 / K_suspension
```

Substituting the measured values,

```
1 / 1907
=
1 / 3364
+
1 / K_suspension
```

which gives

```
K_suspension = 4403 Nm/deg
```

---

## Normalization

Vehicle torsional stiffness depends on suspension wheel rate. The measured stiffness values were normalized by the suspension wheel rate.


```
Normalization factor = 171.92 Nm/deg
```

Normalized stiffness values become

| Component | Normalized Stiffness |
|-----------|---------------------:|
| Monocoque | **19.57** |
| Suspension | **25.61** |

---

## Vehicle Compliance Target

The target was defined so that approximately:

- **90% of total vehicle compliance came from the suspension**
- **10% of total vehicle compliance came from the monocoque and suspension-supporting structures**

This ensured that chassis deformation would have a relatively small influence on suspension tuning. This also balanced the high weight associated with pursuing unnecessaryly high monocoque stiffness.

Using the normalized stiffness values, overall vehicle stiffness is

```
1 / K_vehicle
=
1
+
1 / K_suspension'
+
1 / K_monocoque'
```

where the leading **1** represents tire compliance and the primed values are the normalized stiffness values.

The design target was

```
K_vehicle = 0.90
```

representing a vehicle whose torsional compliance is 90% controlled by the suspension.

Substituting the normalized suspension stiffness,

```
0.10
=
1 /
(
1
+
1 / 25.61
+
1 / K_monocoque,target'
)
```

Solving gives

```
Normalized monocoque target

K_monocoque,target' = 13.86
```

Converting back to physical units,

```
K_monocoque,target
=
13.86 × 171.92
=
2383 Nm/deg
```

Therefore, the minimum design goal for the monocoque was

> **Target Monocoque Torsional Stiffness = 2383 Nm/deg**

---

## Comparison to Measured Performance

The finished monocoque achieved

```
Measured monocoque stiffness = 3364 Nm/deg
```

which exceeds the original design target by approximately **41%**.

Using the measured normalized stiffness,

```
K_vehicle
=
1 /
(
1
+
1 / 25.61
+
1 / 19.57
)
=
0.917
```

This corresponds to

> **91.7% of total vehicle torsional compliance coming from the suspension**, exceeding the original 90% design objective while providing a sufficiently rigid platform for predictable suspension tuning.


<!-- Comparison of Target and Tested-->
<figure class="inline-image-l">
  <img src="{{ '/assets/images/targetstiffness.png' | relative_url }}" alt="Torsional stiffness target calculation">
  <figcaption>Figure Comparing the Targeted and Tested Torsional Stiffness Value</figcaption>
</figure>


## Final Results

The ARG26 monocoque met many primary engineering goals:

- Reduced monocoque laminate mass relative to ARG25
<!-- Weight delta-->
<figure class="inline-image-l">
  <img src="{{ '/assets/weightdelta.png' | relative_url }}" alt="Torsional stiffness target calculation">
  <figcaption>Comparing 2025 Car Weights to 2026 Car Weights</figcaption>
</figure>

- Achieved a measured torsional stiffness of 3,364 N·m/deg, exceeding torsional stiffness goal
- Completed manufacturing in approximately 10 days, which set a new team record for fastest monocoque manufacturing
- Supported an early drive date and an extended vehicle testing campaign




