# Birds' Bones and Living Habits

## About this dataset

There are many kinds of birds: pigeons, ducks, ostriches, penguins… Some are good at flying, others can't fly but run fast. Some swim under water, others wading in shallow pool.

According to their living environments and living habits, birds are classified into different ecological groups. This dataset contains data on 6 particular ecological groups of birds:

- Swimming Birds (SW)
- Wading Birds (W)
- Terrestrial Birds (T)
- Raptors (R)
- Scansorial Birds (P)
- Singing Birds (SO)

Birds belong to different ecological groups have different appearances: flying birds have strong wings and wading birds have long legs. Their living habits are somewhat reflected in their bones' shapes. As data scientists we may think of examining the underlying relationship between sizes of bones and ecological groups , and recognising birds' ecological groups by their bones' shapes.

There are 420 birds contained in this dataset. Each bird is represented by 10 measurements of the birds' bones. All measurements are continuous float numbers (mm) with missing values represented by empty strings. The skeletons of this dataset are collections of Natural History Museum of Los Angeles County. They belong to 21 orders, 153 genera, 245 species.

## Data dictionary

Column name - Description

id -	sequential id. \
huml -	Length of Humerus.\
humw -	Width of Humerus.\
ulnal -	Length of Ulna.\
ulnaw -	Width of Ulna.\
feml -	Length of Femur.\
femw -	Width of Femur.\
tibl -	Length of Tibiotarsus.\
tibw -	Width of Tibiotarsus.\
tarl -	Length of Tarsometatarsus .\
tarw -	Width of Tarsometatarsus .\
type - Ecological Group (SW, W, T, R, P, SO).


## Acknowledgements

This dataset is provided by Dr. D. Liu of Beijing Museum of Natural History.
