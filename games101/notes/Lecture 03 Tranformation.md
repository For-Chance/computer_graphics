# Lecture 03 Tranformation



## 1 Why study transformation？

- modeling
  - scale
- Viewing : projection(3D to 2D)



## 2 2D transformation: rotation, scale, shear

- scale 
  - ![image-20221101164400185](assets/image-20221101164400185-16672923121351.png)

- horizontal reflection

  - horizontal shift
    - vertical shift is always 0
    - ![image-20221101164647142](assets/image-20221101164647142.png)
    - ![image-20221101164736030](assets/image-20221101164736030.png)

- rotation

- linear transforms = matrices

  

## 3 Homogeneous cooridnates

- translation
  - ![image-20221101170554419](assets/image-20221101170554419.png)
  - translation is not linear transform!
- ![image-20221101170818883](assets/image-20221101170818883.png)
- 向量为0：平移不变性
- ![image-20221101171046158](assets/image-20221101171046158.png)
- affine transform $\rightarrow$ using homogenous cooridnate
- Inverse transform
  - ![image-20221101171332916](assets/image-20221101171332916.png)
  - $AA^{-1}=I$
- the order of transforms is import 
  - it means the product don't meet  Exchange law

## 4 Composing transforms

- composing transforms
- decomposing complex transforms

## 5 3D transformations

- ![image-20221101172026656](assets/image-20221101172026656.png)
- 