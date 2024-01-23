# Benchmark_KTA_Rostock

This repository contains the dataset used in the paper "Enhancing Kitchen Activity Recognition: A Benchmark Study of the Rostock KTA Dataset" by Dr. Samaneh Zolfaghari, Teodor Stoev, and Prof. Dr. Kristina Yordanova.

If you use the dataset, please cite the paper using the Bibtex below 

@ARTICLE{10409517,
  author={Zolfaghari, Samaneh and Stoev, Teodor and Yordanova, Kristina},
  journal={IEEE Access}, 
  title={Enhancing Kitchen Activity Recognition: A Benchmark Study of the Rostock KTA Dataset}, 
  year={2024},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/ACCESS.2024.3356352}}


as well as the original KTA dataset paper "Kitchen task assessment dataset for measuring errors due to cognitive impairments" by Yordanova, Kristina and Hein, Albert and Kirste, Thomas

@inproceedings{yordanova2020kitchen,
  title={Kitchen task assessment dataset for measuring errors due to cognitive impairments},
  author={Yordanova, Kristina and Hein, Albert and Kirste, Thomas},
  booktitle={2020 IEEE International Conference on Pervasive Computing and Communications Workshops (PerCom Workshops)},
  pages={1--6},
  year={2020},
  organization={IEEE}
}


# Description of the files
All the archive files containing our data are in the folder *data* which contains two other folders *all_actions* (containing the experimental data and the labels we used for the evaluation of the classifier when trained with all action classes in the KTA dataset), and *actions_most_common* (containing the experimental data and labels we used to evaluate the classifier on the 6 most common actions).

