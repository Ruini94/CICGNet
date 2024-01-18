# CICGNet: Content-illumination Coupling Guided Low-light Image Enhancement Network
## Abstract
##### Low-light enhancement algorithms need to simultaneously deal with problems such as uneven illumination, prone to structural distortion and color oversaturation. This paper proposes a content-illumination coupling guided low-light image enhancement network (CICGNet), it develops a truss topology as backbone, it follows Retinex to decompose low-light image component in an end-to-end way. The preservation of content features and the enhancement of illumination features are carried out along with depth and width direction of the truss topology architecture. The extraction of content component and illumination component consider improving the reusability of features. Illumination component uses pre- and post-activation features at different depth levels. Content component maintains content details in different spatial resolutions simultaneously along depth and width of the network. The decomposition and reconstruction of features are iterated multiple times based on the truss topology, the extracted features in the previous stages are used in subsequent stages. The network progressively enhances the illumination component and maintains the content component based on Retinex. The proposed algorithm demonstrates better performance compared with advanced attention-based low-light enhancement algorithms and state-of-the-art image restoration algorithms. We perform ablation studies and demonstrate the impact of low-light enhancement algorithm on subsequent high-level vision tasks. Code is available at: https://github.com/Ruini94/CICGNet
### 
***
## Experiments

### Dataset Preparation
#### please put datasets in
> data_path
>> trainA  
>> trainB  
>> testA  
>> testB
***
## Usage
### train
#### `python main.py`
### test
#### `python evaluate.py`
