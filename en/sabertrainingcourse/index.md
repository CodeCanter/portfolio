**[`< Projects`](https://codecanter.github.io/portfolio/en/)**

**SaberTrainingCourse** (07.2024 - now)

![06_try_cabbage_canter](https://github.com/user-attachments/assets/ce5fde06-db72-440e-a638-7d9491cb3932)

A horse-drawn saber simulator, developed for Meta Quest 3 goggles, MR mode.
The idea for the project was born around 2018 and was one of the first to introduce me to the secrets of developing software for VR technology, and at the same time be an interesting tool supporting the development of personal interests. The assumptions were also different, mainly due to technical limitations - only stationary mode.
The project is currently at the stage of a proof of concept.

Project assumptions:
- possibility of training in wielding a sabre on horseback (based on - Cavalry Regulations Part I, 1938)
- dynamic variant - MR mode, the user moves on horseback in three gaits, stationary targets
- stationary variant - MR or VR mode, the user is located approximately in one place in space, can use a stationary platform (a dimensional model of a riding horse) or a moving platform (a dimensional model of a horse simulating the movement of the back in the rhythm of a trot or gallop), the application simulates the user "approaching" subsequent decoys at a set speed
- the application evaluates important parameters of wielding the weapon, including correctness of guiding the blade, cutting angle, cutting force, part of the sabre performing the cut
- in order to increase the realism of the exercise (mainly developing muscle memory and a sense of distance), while increasing safety (especially at the initial stages), a model of a sabre was used. 34, similar weight and balance, with attached controller (may want to consider another motion tracking device in the future)

Introduction:
1.  Place dummies
![01_place_target](https://github.com/user-attachments/assets/7a5baa4d-46e6-49f2-b0c8-1f0dd1c0f215)

2.  Get on your mount
![02_mont_a_horse](https://github.com/user-attachments/assets/942f44f6-e050-4387-86e4-b159830ab759)

3.  "Insert carrot coin"
![03_insert_carrot_coin](https://github.com/user-attachments/assets/6462cfb9-95eb-42d6-86de-15b29b6c3662)

4.  Draw your saber
![04_draw_your_saber](https://github.com/user-attachments/assets/ba9fca88-1109-4831-b5ca-c356648aaec3)

5.  Check tracking accuracy
![05_try_if_works_fine](https://github.com/user-attachments/assets/82de50d3-5a88-4f84-b243-f507f7ecd883)   ![08_stationary_cabbage](https://github.com/user-attachments/assets/630014cc-1aae-4734-afa6-295b36722371)

6.  Practice until you master it
![06_try_cabbage_canter](https://github.com/user-attachments/assets/ce5fde06-db72-440e-a638-7d9491cb3932)   ![09_stationary_fast_targets](https://github.com/user-attachments/assets/dd290a78-d265-4835-8b11-6331cfa5a8d0)

Identified issues/limitations:
- movement limitation in Quest 3 headset in a 5 x 5m space (message "You've moved too far") - problem solved by disabling "Physical space features"
- tracking lost when moving in a larger space - problem solved by enabling "Travel mode"
![_tracking_error](https://github.com/user-attachments/assets/eef501c6-4e5c-4d55-990d-197a521c7aaa)

**[`< Projects`](https://codecanter.github.io/portfolio/en/)**
