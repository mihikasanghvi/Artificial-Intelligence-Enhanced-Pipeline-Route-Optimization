# Artificial Intelligence Enhanced Pipleine Route Optimization

## Abstract
The development of efficient and cost-effective pipeline routes is crucial for the energy industry, necessitating strategic planning to determine optimal paths. This project endeavors to address this need by designing an intelligent pipeline route optimization system that integrates Geographic Information Systems (GIS), Remote Sensing (RS) technologies, machine learning models, and Multi-Criteria Decision-Making (MCDM) techniques. Leveraging advanced technologies and methodologies, such as machine learning and deep learning models, the research seeks to enhance the accuracy of classifying and analyzing geospatial datasets, ultimately contributing valuable insights to geographical information systems, remote sensing, and infrastructure planning.

The evolution of pipeline route selection methodologies highlights a progression from early GIS-based models to more integrated and sophisticated approaches over the decades. While challenges persist, including data limitations and technical hurdles, the project's methodology adopts a comprehensive and integrated approach to overcome these obstacles. By leveraging AI and DL techniques coupled with GIS-based spatial multicriteria decision-making methods, the research aims to push the boundaries of accuracy in pipeline route optimization. This study examines the Dadri-Panipat Network in the North and the Hazira-Ankleshwar Pipeline in the West, showcasing the versatility of the approach across diverse pipeline networks in India.

The limitations of current LULC methods include a lack of integration of advanced deep learning (DL) models, training on region-specific datasets leading to biased performance, and under-representation of certain LULC classes. To address these limitations, this study utilizes the Sentinel-2 LULC dataset, comprising over 213,750 pre-processed 10 m resolution images representing seven distinct classes of Land Use Land Cover, thereby representing a diverse and versatile region. Six deep learning models are employed for training and testing: LinkNet Inceptionv3, LinkNet ResNet152, UNet ResNext101, UNet Inception ResNetv2, UNet DenseNet169, and UNet EfficientNetb7 with accuracies ranging from 92\%-96\%. The performance of these models is compared to determine the most suitable model for LULC classification, which can subsequently be employed for further route planning applications. The UNet EfficientNetb7 model emerged as the best-performing, with high training accuracy and validation accuracy. 

The study employed Multi-Criteria Decision-Making and Analytic Hierarchy Process (AHP) to prioritize route selection factors systematically. Various AI heuristics, including Dijkstra's Algorithm and A* algorithm variants, were used for route optimization, aiming to minimize pipeline length while considering land use/land cover (LULC) priorities. In the implementation of AHP, the relative importance of seven LULC classes was determined, with urban areas, dense forests, farms, and water bodies identified as crucial. Dijkstra's Algorithm efficiently allocated the pipeline through barren lands and sparse forests, achieving the most optimized route.

In the Dadri-Panipat study area, the original pipeline length was approximately 206.22 kilometers, while the optimized distance ranged from 143.17 to 150.44 kilometers, showcasing notable reductions in pipeline length. Similarly, in the Hazira-Ankleshwar study area, the original pipeline route spanned approximately 90 kilometers, whereas the optimized distances ranged from around 55 to 77.65 kilometers. The study highlights the significance of adopting an interdisciplinary approach for sustainable and environmentally conscious infrastructure development, paving the way for intelligent approaches in pipeline optimization.

## Publication
Application of Geospatial Technology and Modelling on Natural Resources Management - Current State, Challenges and Sustainability” 

It will be published in Springer Advances in Geographic Information Science Book Series (Indexed in Scopus). 

Springer International Publishing, Springer Nature Switzerland AG (Publisher)

## Contact
- **GitHub**: [mihikasanghvi]((https://github.com/mihikasanghvi))
