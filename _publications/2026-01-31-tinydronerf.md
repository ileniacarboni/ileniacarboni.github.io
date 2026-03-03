---
title: "Tiny-DroNeRF: Tiny Neural Radiance Fields aboard Federated Learning-enabled Nano-drones"
collection: publications
category: conferences
#permalink: /publication/2009-10-01-paper-title-number-1
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2026-01-31
venue: 'IEEE Conference on Robotics and Automation (ICRA) 2026'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://arxiv.org/abs/2603.01850'
bibtexurl: 'http://ileniacarboni.github.io/files/tinydronerf.bib'
citation: 'Carboni I., Cereda E., Lamberti L., Malpetti D., Conti F., and Palossi D. (2026). &quot;Tiny-DroNeRF: Tiny Neural Radiance Fields aboard Federated Learning-enabled Nano-drones.&quot; 2026</i>'
---
To appear in *Proceedings of the 2026 IEEE International Conference on Robotics and Automation (ICRA), 2026*

Sub-30g nano-sized aerial robots can leverage their agility and form factor to autonomously explore cluttered and narrow environments, like in industrial inspection and search and rescue missions. However, the price for their tiny size is a strong limit in their resources, i.e., sub-100 mW microcontroller units (MCUs) delivering ∼100 GOps/s at best, and memory budgets well below 100 MB. Despite these strict constraints, we aim to enable complex vision-based tasks aboard nano-drones, such as dense 3D scene reconstruction: a key robotic task underlying fundamental capabilities like spatial awareness and motion planning. Top-performing 3D reconstruction methods leverage neural radiance fields (NeRF) models, which require GBs of memory and massive computation, usually delivered by high-end GPUs consuming 100s of Watts. Our work introduces Tiny-DroNeRF, a lightweight NeRF model, based on Instant-NGP, and optimized for running on a GAP9 ultra-low-power (ULP) MCU aboard our nano-drones. Then, we further empower our Tiny-DroNeRF by leveraging a collaborative federated learning scheme, which distributes the model training among multiple nano-drones. Our experimental results show a 96% reduction in Tiny-DroNeRF's memory footprint compared to Instant-NGP, with only a 5.7 dB drop in reconstruction accuracy. Finally, our federated learning scheme allows Tiny-DroNeRF to train with an amount of data otherwise impossible to keep in a single drone's memory, increasing the overall reconstruction accuracy. Ultimately, our work combines, for the first time, NeRF training on an ULP MCU with federated learning on nano-drones.