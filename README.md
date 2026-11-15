# ARIN5101 Course Project - CNN Comparison on an 80-class CIFAR-100 Subset

## Dataset Description
Dataset size:  
Training set: 32,000 images  
Validation set:  8,000 images  
Test set: 8,000 images  
Per class: 400 training, 100 validation and 100 test images  
Image size: 32 * 32 RGB  

The selected classes are:  
       0. aquatic_mammals: dolphin, seal, whale, otter  
       1. fish: shark, trout, ray, flatfish  
       2. flowers: rose, sunflower, tulip, orchid  
       3. food_containers: bottle, cup, bowl, plate  
       4. fruit_and_vegetables: apple, pear, orange, mushroom  
       5. household_electrical_devices: clock, lamp, television, keyboard  
       6. household_furniture: chair, table, couch, bed  
       7. insects: beetle, butterfly, bee, caterpillar  
       8. large_carnivores: lion, tiger, bear, leopard  
       9. large_man_made_outdoor_things: bridge, castle, house, road  
      10. large_natural_outdoor_scenes: mountain, sea, forest, cloud  
      11. large_omnivores_and_herbivores: elephant, camel, kangaroo, chimpanzee  
      12. medium_mammals: fox, raccoon, skunk, possum  
      13. non_insect_invertebrates: crab, lobster, snail, spider  
      14. people: man, woman, girl, boy  
      15. reptiles: crocodile, turtle, snake, lizard  
      16. small_mammals: rabbit, hamster, mouse, squirrel  
      17. trees: palm_tree, pine_tree, oak_tree, maple_tree  
      18. vehicles_1: bus, motorcycle, bicycle, pickup_truck  
      19. vehicles_2: rocket, tank, tractor, streetcar  
The fine labels are remapped to 0-79 for training  

## Environment
  Python 3.14.6  
  PyTorch 2.14.1  
  torchversion 0.29.1  
  CUDA 12.6  
  NumPy 2.5.3  
  Matplotlib 3.11.0  
  Pillow 12.3.0  
  
