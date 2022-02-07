# Datasets and pretrained Models for StyleGAN3
<b>Dear arfiticial friend, this is a collection of artistic datasets and models that we have put together during our ongoing stylegan3 trip at the <i>lucid layers</i> studios. You can use the model snapshots for instant fun, or you can work with the source datasets to train your own models.</b><br>
Some models include multiple snapshots. these can give interesing variations.
<br><br><i>You are welcomed to use everything for your own purposes, but please include a link to this repo in your work.</i><br>
<br>
### Updates
</b>This Document will be updated frequently</b> since most of our models are still in training on higher resolution.
You find information on updates in the "releases" section on the right. (you may "watch" this repo for getting notified on new models)
### Progress
- [x] prepare all datasets in resolutions 256, 512, 1024
- [ ] train each datasets in 256
- [ ] train each datasets in 512
- [ ] train each datasets in 1024


# ... based on "Wombo Dream":
All source images in this category were generated with [Wombo Dream](https://www.wombo.art/). thanks to the solid api implementation of [adri326](https://github.com/adri326/wombot) we could remotely generate thousands of images.
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
  <details><Summary>Model: <i>256 px</i></summary>
  
  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 29 kimg<br>[Download .pkl](https://www.dropbox.com/s/v2oie53cz62ozvu/network-snapshot-000029.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152698796-c0f3285f-765a-4238-bb71-635e669f346b.jpg" height=150>&nbsp;![network-snapshot-000029 pkl](https://user-images.githubusercontent.com/10214666/152711494-408f0019-ce36-4114-8442-494eec6e5ba6.gif) |  
  | 05 kimg<br>[Download .pkl](https://www.dropbox.com/s/9f39drloh9x7oes/network-snapshot-000005.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152698953-7b4a3a08-84f7-4e8e-a2cf-f35359a2a39e.jpg" height=150>&nbsp; ![network-snapshot-000005 pkl](https://user-images.githubusercontent.com/10214666/152711502-ab1a0e6e-19a1-45e1-b23a-ee2c8229dbe9.gif) |  
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
  <details><Summary>Model: <i>256 px</i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 68 kimg<br>[Download .pkl](https://www.dropbox.com/s/o33lhgnk91hstvx/network-snapshot-000069.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152802322-c514368c-3f54-4354-b5cf-7933efed4cab.jpg" height=150>![network-snapshot-000067 pkl](https://user-images.githubusercontent.com/10214666/152802351-41ec2c1a-73e4-4bd7-8d77-de2acaf19b82.gif) |   
  | 12 kimg<br>[Download .pkl](https://www.dropbox.com/s/36gq2zwb0p3fo1f/network-snapshot-000012.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152699361-eb1bf9e6-1ec9-4503-8c69-f5f27e79e475.jpg" height=150>![network-snapshot-000012 pkl](https://user-images.githubusercontent.com/10214666/152711526-ba909f26-0412-4507-a6f5-a4f61d2427b4.gif) |  
 
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
  <details><Summary>Model: <i>256 px</i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 38 kimg<br>[Download .pkl](https://www.dropbox.com/s/gur14k0e7kspguy/network-snapshot-000038.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152700055-317ba7e7-a1e9-45e4-ad53-f3e4721c11c4.jpg" height=150>![network-snapshot-000038 pkl](https://user-images.githubusercontent.com/10214666/152711543-7306b1c6-1444-4331-8658-d6da6b8812ca.gif) |  
 
  </details>
  






## 4. forest daemons <img src="https://user-images.githubusercontent.com/10214666/152700584-add73b02-f8b7-4b2c-b46c-ec2529f8659d.jpg" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | forest daemons |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 794 |
| Dataset download | [256](https://www.dropbox.com/s/anj5eolzsr6ikp2/forrest_daemons.256.zip?dl=0), [512](https://www.dropbox.com/s/zs975iqucpl4mxc/forrest_daemons.512.zip?dl=0), [1024](https://www.dropbox.com/s/74fkrbsnqhiwu84/forrest_daemons.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152701197-7571c2ab-da31-49ee-83df-14e7fa55c15f.jpg" height=150> |
  
  </details>
  <details><Summary>Model: <i>256 px</i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 18 kimg<br>[Download .pkl](https://www.dropbox.com/s/26muctr2eq4br6l/network-snapshot-000018.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152701433-2c2286f3-cd52-4252-8a04-a99f4c45a292.jpg" height=150>![network-snapshot-000018 pkl](https://user-images.githubusercontent.com/10214666/152711570-e9e24d08-6fbb-4e63-93c6-98a392fa70d4.gif) |  
  | 03 kimg<br>[Download .pkl](https://www.dropbox.com/s/rojv7v791a3keqj/network-snapshot-000003.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706541-db11aaea-a14b-411c-a288-77d8c3799605.jpg" height=150> ![network-snapshot-000003 pkl](https://user-images.githubusercontent.com/10214666/152711576-b45ba06c-216b-43a9-bf04-44660fa52707.gif) |  
 
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
  <details><Summary>Model: coming soon ...<i></i></summary>

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
  <details><Summary>Model: coming soon ...<i></i></summary>

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
  <details><Summary>Model: 256 px<i></i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 210 kimg<br>[Download .pkl](https://www.dropbox.com/s/1kfsmlct4mriphc/network-snapshot-000210.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152702636-0706f294-5910-4546-b43a-769d56e0b1b3.jpg" height=150>&nbsp;![network-snapshot-000210 pkl](https://user-images.githubusercontent.com/10214666/152711020-d448d753-90db-4da4-b019-043c56edd024.gif) |  
  | 018 kimg<br>[Download .pkl](https://www.dropbox.com/s/g33kht86vdzummk/network-snapshot-000018.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706385-fd258fca-02bf-4599-8cfa-50f6dce79422.jpg" height=150>&nbsp;![network-snapshot-000018 pkl](https://user-images.githubusercontent.com/10214666/152710822-eefafae9-db82-4e3f-ad6f-fe6660b04f85.gif) |  
  | 013 kimg<br>[Download .pkl](https://www.dropbox.com/s/o874sdoo1iuowqy/network-snapshot-000013.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706389-d9c60c4a-abb9-4a82-9b59-a644ece8c9cc.jpg" height=150>&nbsp;![network-snapshot-000013 pkl](https://user-images.githubusercontent.com/10214666/152710829-f4c63191-645b-4a82-b682-22b4ef036bfd.gif) |  
  | 008 kimg<br>[Download .pkl](https://www.dropbox.com/s/7fmjlc8vje15m6v/network-snapshot-000008.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706387-8ad6884b-7ea6-4c20-a612-8a58f4a46e91.jpg" height=150>&nbsp;![network-snapshot-000008 pkl](https://user-images.githubusercontent.com/10214666/152710832-89de4fe1-40a9-4477-805c-370756ff0e15.gif) |  
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
  <details><Summary>Model: 256<i></i></summary>


  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 168 kimg<br>[Download .pkl](https://www.dropbox.com/s/02br3mjkma1hubc/network-snapshot-000162.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152720364-b81f55c2-5da1-48be-ab3d-338da3ab5fbc.jpg" height=150>![network-snapshot-000162 pkl](https://user-images.githubusercontent.com/10214666/152720383-4fbf252a-bd1e-4f31-841c-5ce5ec2b7026.gif)  |   
  | 128 kimg<br>[Download .pkl](https://www.dropbox.com/s/6lwn7c9y0i952ew/network-snapshot-000128.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706249-716a09ca-09e9-4f0e-89e6-7c0482669d6f.jpg" height=150>![network-snapshot-000128 pkl](https://user-images.githubusercontent.com/10214666/152711602-89ddd131-21ef-4ba5-92d8-5056360b50fe.gif) | 
  | 13 kimg<br>[Download .pkl](https://www.dropbox.com/s/nqpq11gcsu0e7yw/network-snapshot-000013.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706247-7142c170-6b05-4780-b02c-e48a88eec2be.jpg" height=150>![network-snapshot-000013 pkl](https://user-images.githubusercontent.com/10214666/152711596-291a5143-d162-40f5-ac14-ca2a42bbf424.gif) | 
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
  | 19 kimg<br>[Download .pkl](https://www.dropbox.com/s/g14lsdbohuk2oco/network-snapshot-000019.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706153-747c0f7d-344a-4430-acf8-48768626bcd0.jpg" height=150>![network-snapshot-000019 pkl](https://user-images.githubusercontent.com/10214666/152711637-5c399520-b27d-4cf3-a071-4c605439432b.gif) |  
 
  </details>
  <details><Summary>Model 512x512 <i></i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [affhq]() |
  | Resolution | 512x512 |
  | 236 kimg<br>[Download .pkl](https://www.dropbox.com/s/yzraojzmg2kybjx/network-snapshot-000236.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706105-573d831e-2c49-4608-8f9b-2792f5cc95ce.jpg" height=150>![network-snapshot-000236 pkl](https://user-images.githubusercontent.com/10214666/152711650-d4b7b43c-d1c1-42cd-aaf2-53429ee91829.gif) |  
  | 004 kimg<br>[Download .pkl](https://www.dropbox.com/s/ysmm501vtv50mze/network-snapshot-000004.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152706125-71881111-6645-4db0-8358-947ee7e4005b.jpg" height=150>![network-snapshot-000004 pkl](https://user-images.githubusercontent.com/10214666/152711645-4a48e380-fee4-4ed3-af13-566a230f9dcc.gif) | 
  </details>









  ## 10. eternal planet earth <img src="https://user-images.githubusercontent.com/10214666/152715323-e10c38c7-e41b-4319-b8a0-54e4db1080f7.png" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | eternal planet earth |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 1323 |
| Dataset download | [256](https://www.dropbox.com/s/0m12uho06piad9k/eternal_love_for_planet_earth.256.zip?dl=0), [512](https://www.dropbox.com/s/cp88cebhxiudfy4/eternal_love_for_planet_earth.512.zip?dl=0), [1024](https://www.dropbox.com/s/ju9k9j0oxovjp7g/eternal_love_for_planet_earth.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152715232-e3d7d0e3-ed64-40be-a729-18ff5a4bcf90.jpg" height=150> |  
  
  </details>
  <details><Summary>Model: coming soon ...<i></i></summary>

  </details>







  ## 11. mechanical landscape madness <img src="https://user-images.githubusercontent.com/10214666/152718081-be89b510-3678-4fea-b0f5-5feb7bc56dcf.png" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | mechanical landscape madness  |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 1269 |
| Dataset download | [256](https://www.dropbox.com/s/1cx5o001lj2wmfg/mech_landsc_madn.256.zip?dl=0), [512](https://www.dropbox.com/s/zd58xwyb9iy6ro2/mech_landsc_madn.512.zip?dl=0), [1024](https://www.dropbox.com/s/yjiy4mtdp6ql9uv/mech_landsc_madn.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152718110-629afb83-2b9d-4743-9a7a-b1fed31f74ba.jpg" height=150> |  
  
  </details>
  <details><Summary>Model 256x256 <i></i></summary>

  |    |   |
  | --- | --- |
  | Method | stylegan3-t, Transfer learning from [Landscape256]() |
  | Resolution | 256x256 |
  | 6 kimg<br>[Download .pkl](https://www.dropbox.com/s/5oar443k7iw3qvp/network-snapshot-000006.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152721194-cdd940e3-2ab4-479c-9a26-629a47b91f36.jpg" height=150>![network-snapshot-000006 pkl](https://user-images.githubusercontent.com/10214666/152721211-1390e532-ea99-4cc7-84d4-846292ddcebc.gif) |  
  | 5 kimg<br>[Download .pkl](https://www.dropbox.com/s/g3asjz3yn4ub1c5/network-snapshot-000005.pkl?dl=0) | <img src="https://user-images.githubusercontent.com/10214666/152721192-378eb256-133f-4c2c-80b2-71df6fadd3cb.jpg" height=150>![network-snapshot-000005 pkl](https://user-images.githubusercontent.com/10214666/152721202-b7ab3aae-b400-4ae7-a776-6daf0a1a6071.gif) |  
  </details>



  ## 12. two aliens speaking <img src="https://user-images.githubusercontent.com/10214666/152798772-9a5de403-0f12-4e59-bab2-0e23c95560fb.jpg" align="right" width=120 > 
<details><Summary>Dataset</summary>

|    |   |
| --- | --- |
| Name | two_aliens_speaking |
| Method | [Wombo Dream](https://www.wombo.art/) via [Wombot](https://github.com/adri326/wombot) |
| Image count | 1159 |
| Dataset download | [256](https://www.dropbox.com/s/46sa9szcnojg41b/two_aliens_speaking.256.zip?dl=0), [512](https://www.dropbox.com/s/i3dj5i2sh8prxur/two_aliens_speaking.512.zip?dl=0), [1024](https://www.dropbox.com/s/rc9p330t68dj3zh/two_aliens_speaking.1024.zip?dl=0) |
| Samples | <img src="https://user-images.githubusercontent.com/10214666/152798793-4886479a-5893-4ee5-98d0-6fa62b20730e.png" height=150> |
  
  </details>
  <details><Summary>Model: coming soon... <i></i></summary>
 
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
  | 00 kimg<br>[Download .pkl]() | <img src="" height=150> |  
 
  </details>
-->
## Contribution
If you do continue training on a model, or train a dataset in a high resolution, it would be great to include that in this list.<br>(please send me a link to your .pkl file in the "[issues](https://github.com/edstoica/lucid_stylegan3_models/issues)" tab)</i>
<br>Also, if you made some images or videos you like to share - we would love to see your work! put everything in the issues...
## License
You are welcomed to use all files for your own (commercial) purposes, but please include a link to this repo in your work. Thank you.
