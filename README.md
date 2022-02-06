# Datasets and Models for StyleGAN3
This is a collection of artistic datasets and models that we have created during our ongoing stylegan3 trip.
You may like to use the model snapshots* for instant fun, or you can work with the source datasets.
<br><br><i>*You are welcomed to use the models for your own purposes as long as you include a link to this repo in your work.</i>
# ... based on "Wombo Dream":
All source images in this category were generated with [Wombo Dream](https://www.wombo.art/). thanks to the api implementation of [adri326](https://github.com/adri326/wombot) we could remotely generate thousands of images.
these images were cropped to center and scaled to 1024x1024. datasets in resolutions of 256, 512 and 1024 were generated and are available for download.

## 1. Mechanical devices from the future <img src="https://user-images.githubusercontent.com/10214666/152695339-9e6bb3b3-bd4e-4884-82b5-d1c2d3ac8cb3.png" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | Mechanical devices from the future |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 2169 |
| Dataset download | [256](https://www.dropbox.com/s/luan4zn11az3jfi/mech_dev_future.256.zip?dl=0), [512](https://www.dropbox.com/s/ov4nbcn457qp0ux/mech_dev_future.512.zip?dl=0), [1024](https://www.dropbox.com/s/mkt2z98atp9gru1/mech_dev_future.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152695339-9e6bb3b3-bd4e-4884-82b5-d1c2d3ac8cb3.png" width=150><img src="https://user-images.githubusercontent.com/10214666/152695348-745399e1-d145-4273-b4af-ee8b23179dc7.png" width=150><img src="https://user-images.githubusercontent.com/10214666/152695351-9e0548a9-1e6b-44e2-8423-32fbf03406a4.png" width=150><img src="https://user-images.githubusercontent.com/10214666/152695358-c8c47ea4-b5b6-4368-a11f-dc7cce9125e3.png" width=150> |  
  </details>
  <details><Summary>Model: <i>mech_dev.256.pkl</i></summary>
  
  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 29 kimg<br>[Download](https://www.dropbox.com/s/v2oie53cz62ozvu/network-snapshot-000029.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152698796-c0f3285f-765a-4238-bb71-635e669f346b.jpg" height=150> |  
  | 05 kimg<br>[Download](https://www.dropbox.com/s/9f39drloh9x7oes/network-snapshot-000005.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152698953-7b4a3a08-84f7-4e8e-a2cf-f35359a2a39e.jpg" height=150> |  
  </details>
  
  
  
  

## 2. Vivid Flowers <img src="https://user-images.githubusercontent.com/10214666/152699193-96be1271-7e4c-4d8a-8978-3386588b3216.png" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | Vivid Flowers |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 793 |
| Dataset download | [256](https://www.dropbox.com/s/k5a6bsmtwqk9vok/flowers.256.zip?dl=0), [512](https://www.dropbox.com/s/i4zlkesyi8c93zf/flowers.512.zip?dl=0), [1024](https://www.dropbox.com/s/b7sc7i4lehnci1k/flowers.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152699137-dc389292-2ab7-4703-a0d5-d00ca5c0e8af.jpg" height=150> |
  
  </details>
  <details><Summary>Model: <i>vivid_flowers.256.pkl</i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 12 kimg<br>[Download](https://www.dropbox.com/s/36gq2zwb0p3fo1f/network-snapshot-000012.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152699361-eb1bf9e6-1ec9-4503-8c69-f5f27e79e475.jpg" height=150> |  
 
  </details>










## 3. Alien with Sunglasses <img src="https://user-images.githubusercontent.com/10214666/152700037-4a7c3b98-8c34-4f1f-9620-05e6b35306f6.png" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | Alien Sunglasses |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 1600 |
| Dataset download | [256](https://www.dropbox.com/s/ae81twlf39s0ao3/alien_sunglasses.256.zip?dl=0), [512](https://www.dropbox.com/s/8y10fxqmbqeg5h4/alien_sunglasses.512.zip?dl=0), [1024](https://www.dropbox.com/s/4t72b8g2o65s3ns/alien_sunglasses.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152700237-cbfa093f-83d4-4f03-9c6d-ba998f790483.png" height=150> |
  
  </details>
  <details><Summary>Model: <i>alien_sunglasses.256.pkl</i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 38 kimg<br>[Download](https://www.dropbox.com/s/gur14k0e7kspguy/network-snapshot-000038.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152700055-317ba7e7-a1e9-45e4-ad53-f3e4721c11c4.jpg" height=150> |  
 
  </details>
  






## 4. forrest daemons <img src="https://user-images.githubusercontent.com/10214666/152700584-add73b02-f8b7-4b2c-b46c-ec2529f8659d.jpg" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | forrest daemons |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 794 |
| Dataset download | [256](https://www.dropbox.com/s/anj5eolzsr6ikp2/forrest_daemons.256.zip?dl=0), [512](https://www.dropbox.com/s/zs975iqucpl4mxc/forrest_daemons.512.zip?dl=0), [1024](https://www.dropbox.com/s/74fkrbsnqhiwu84/forrest_daemons.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152701197-7571c2ab-da31-49ee-83df-14e7fa55c15f.jpg" height=150> |
  
  </details>
  <details><Summary>Model: <i>forrest_daemons.256.pkl</i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 18 kimg<br>[Download](https://www.dropbox.com/s/26muctr2eq4br6l/network-snapshot-000018.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152701433-2c2286f3-cd52-4252-8a04-a99f4c45a292.jpg" height=150> |  
  | 03 kimg<br>[Download](https://www.dropbox.com/s/rojv7v791a3keqj/network-snapshot-000003.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706541-db11aaea-a14b-411c-a288-77d8c3799605.jpg" height=150> |  
 
  </details>
  
  

  
  



## 5. third eye watching you <img src="https://user-images.githubusercontent.com/10214666/152700663-aaf208ee-3d24-4659-bf90-7265a154224f.jpg" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | third eye watching you |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 1363 |
| Dataset download | [256](https://www.dropbox.com/s/l953cktli9yzhnu/third_eye_watching.256.zip?dl=0), [512](https://www.dropbox.com/s/1lcvqm113r5ycob/third_eye_watching.512.zip?dl=0), [1024](https://www.dropbox.com/s/ndzq26kzoabs90h/third_eye_watching.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152702468-5688299c-0e43-4e91-96ce-e3a2ebee15d0.jpg" height=150> |
  
  </details>
  <details><Summary>Model: <i></i></summary>

  coming soon ...
  
  </details>







  ## 6. mars spaceport <img src="https://user-images.githubusercontent.com/10214666/152702104-44395a9c-e069-47b7-aab7-c9545fec297b.png" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | mars spaceport |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 710 |
| Dataset download | [256](https://www.dropbox.com/s/oho0aciounn1a4p/mars_spaceport.256.zip?dl=0), [512](https://www.dropbox.com/s/cb8a409227exq4k/mars_spaceport.512.zip?dl=0), [1024](https://www.dropbox.com/s/54m70eytqj47plr/mars_spaceport.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152702191-9066ad1f-339c-4a04-a11b-5eb94de4fcae.jpg" height=150> |
  
  </details>
  <details><Summary>Model: <i></i></summary>

  coming soon ...
  
  </details>





  ## 7. scifi city <img src="https://user-images.githubusercontent.com/10214666/152702819-59236aa5-de91-466e-ac0b-4428d6c3fb00.jpg" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | scifi city |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 1245 |
| Dataset download | [256](https://www.dropbox.com/s/8ttrikdorw8v8cw/a_scifi_city.256.zip?dl=0), [512](https://www.dropbox.com/s/xopgfowlgvqisuf/a_scifi_city.512.zip?dl=0), [1024](https://www.dropbox.com/s/vzqefxmz27ukpzs/a_scifi_city.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152703422-bc5e72c8-c349-422a-be60-5d2aa3b49eeb.jpg" height=150> |
  
  </details>
  <details><Summary>Model: scifi_city.256.pkl<i></i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 210 kimg<br>[Download](https://www.dropbox.com/s/1kfsmlct4mriphc/network-snapshot-000210.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152702636-0706f294-5910-4546-b43a-769d56e0b1b3.jpg" height=150> |  
  | 018 kimg<br>[Download](https://www.dropbox.com/s/g33kht86vdzummk/network-snapshot-000018.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706385-fd258fca-02bf-4599-8cfa-50f6dce79422.jpg" height=150> |  
  | 013 kimg<br>[Download](https://www.dropbox.com/s/o874sdoo1iuowqy/network-snapshot-000013.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706389-d9c60c4a-abb9-4a82-9b59-a644ece8c9cc.jpg" height=150> |  
  | 008 kimg<br>[Download](https://www.dropbox.com/s/7fmjlc8vje15m6v/network-snapshot-000008.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706387-8ad6884b-7ea6-4c20-a612-8a58f4a46e91.jpg" height=150> |  
  </details>





  ## 8. scifi spaceship <img src="https://user-images.githubusercontent.com/10214666/152702994-1fc272e8-7b4d-4f31-baf7-64a02d67d7d8.png" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | scifi spaceship |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 1108 |
| Dataset download | [256](https://www.dropbox.com/s/34oajoz0v931vlw/a_scifi_space_ship.256.zip?dl=0), [512](https://www.dropbox.com/s/0ilbpcdn413ivr5/a_scifi_space_ship.512.zip?dl=0), [1024](https://www.dropbox.com/s/iidpx8ta0v7kc1i/a_scifi_space_ship.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152702989-865643b1-91de-461b-9259-83c65425ded1.jpg" height=150> |
  
  </details>
  <details><Summary>Model: <i></i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 128 kimg<br>[Download](https://www.dropbox.com/s/6lwn7c9y0i952ew/network-snapshot-000128.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706249-716a09ca-09e9-4f0e-89e6-7c0482669d6f.jpg" height=150> | 
  | 13 kimg<br>[Download](https://www.dropbox.com/s/nqpq11gcsu0e7yw/network-snapshot-000013.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706247-7142c170-6b05-4780-b02c-e48a88eec2be.jpg" height=150> | 
  </details>






  ## 9. yellow comic alien <img src="https://user-images.githubusercontent.com/10214666/152703766-446ff8cd-213e-4688-a573-3788cc6b0535.png" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | yellow comic alien |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 3984 |
| Dataset download | [256](https://www.dropbox.com/s/6r5t53p7s19g76d/alien256.zip?dl=0), [512](https://www.dropbox.com/s/fopu5jvzot7swdc/alien512.zip?dl=0), [1024](https://www.dropbox.com/s/qdcgakyrz8u324a/alien1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152703771-b0d20e09-c320-4557-8628-ba55cf1d21c2.jpg" height=150> |
  
  </details>
  <details><Summary>Model 256x256 <i></i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 19 kimg<br>[Download](https://www.dropbox.com/s/g14lsdbohuk2oco/network-snapshot-000019.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706153-747c0f7d-344a-4430-acf8-48768626bcd0.jpg" height=150> |  
 
  </details>
  <details><Summary>Model 512x512 <i></i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [affhq]() |
  | Resolution | 512x512 |
  | 236 kimg<br>[Download](https://www.dropbox.com/s/yzraojzmg2kybjx/network-snapshot-000236.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706105-573d831e-2c49-4608-8f9b-2792f5cc95ce.jpg" height=150> |  
  | 004 kimg<br>[Download](https://www.dropbox.com/s/ysmm501vtv50mze/network-snapshot-000004.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706125-71881111-6645-4db0-8358-947ee7e4005b.jpg" height=150> | 



  </details>

<!--
<br><br><br><br><br><br><br><br><br>
  ## x. template <img src="" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name |  |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count |  |
| Dataset download | [256](), [512](), [1024]() |
| Samples | <img src="" height=150> |
  
  </details>
  <details><Summary>Model: <i></i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 00 kimg<br>[Download]() | <img src="" height=150> |  
 
  </details>
-->
