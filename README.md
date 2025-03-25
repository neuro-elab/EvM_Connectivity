# Connecto

The Connecto app provides researchers with the processed data presented in the article _'E. van Maren, C. G. Mignardot, R. Widmer, C. Friedrichs-Maeder, P. Nevalainen, M. Fuchs, J. Anso, C. Pollo, A. Tzovara, T. Proix, K. Schindler, M. O. Baud, **Directed cortico-limbic dialogue in the human brain**'_. Researchers can independently explore this data, gaining deeper insights into the newly revealed measurements, such as directionality and response probability.

The Connecto app is available for Windows and Mac. 
It has been developed by Dr. Ellen van Maren, Roland Widmer, and Dr. Camille G. Mignardot from the e-lab, Department of Neurology, Bern Inselspital (University Hospital of Bern), Bern, Switzerland, directed by Prof. Maxime Baud, M.D. Ph.D.

## Guidelines

### 1. Data Selection
In the panel on the left, select one or several subjects in the first dropdown menu.
Then select which hemisphere you would like to see (both hemispheres, both hemispheres merged in a single left hemisphere, only right or only left hemisphere).

Finally, select regions or tracts of interest. You can select one or several items from the same dropdown menu but you cannot select at the same time regions and tracts.

The list of Destrieux regions encompassed in each selectable region can be obtained in the menu bar under Infos/Region abbreviations.

### 2. Measurement
In the panel on the left, under "Measurements", you can select which measurement is displayed on the inflated brains, connectivity map, and connectograms. The description of the measurements is accessible in the menu bar under Infos/Measurements.

In the special case of "Magnitude" as measurement, you can see the ▶️ button. Pressing ▶️ will show the CCEP propagation on an inflated brain from t=0s (the time when the selected regions/tracts are stimulated) to t=0.4s.

Some measurements are represented on two inflated brains and two connectograms: incoming and outgoing. Incoming shows the regions in which stimulations activate the selected regions (selected regions are receiving). Outgoing depicts the regions that respond to stimulation from the selected regions (selected regions are activating). For measurements with symmetric Incoming/Outgoing visualization, only one inflated brain and one connectogram are displayed.

### Glass brain
On the glass brain, the electrode contacts corresponding to the data selection are shown as dots. If tracts are selected, they are drawn as a bunch of fibers. If regions are selected, the pial surface corresponding to the selected regions is colored in translucent red.

### Inflated brain
On the inflated brain, the selected measurement is either represented as colored Destrieux regions or as colored patches at electrode contacts. You can switch from one representation to the other in the menu bar under View/Inflated brain/Display by ... 

In the case of a display by electrode contacts on the inflated brain, you can choose the threshold to apply to the spreading of the patches in the menu bar under View/Inflated brain/Threshold by ... 


Additionally, you can add overlays to the inflated brain:
  - electrode contacts as dots: in the menu bar under View/Inflated brain/Show electrode contacts
  - delimitation of the Destrieux regions: in the menu bar under View/Inflated brain/Show Destrieux
  - regions*: in the menu bar under View/Inflated brain/Show regions

*_This option is mutually exclusive with the visualization of the selected measurement on the inflated brains_

### Connectivity map
The rows display all regions that were stimulated for the selected subjects. The columns display all regions that were recorded for the selected subjects. The map is colored based on the selected measurement, and its color code is drawn on the bottom.
Hovering the connectivity map with the cursor will display the names of the stimulation and response regions.

### Connectogram
_Description of connectogram_
For some measurements, the strength of the connection is represented by the thickness of the link (the stronger the connection, the thicker the line).

## Troubleshooting
For Mac users, the app can be blocked at launch. To solve it, depending on your macOS environment, you have two possibilities:
  - a. right-click on the app and select "Open". Then confirm you want to open. 
  - b. open System Settings, go to Privacy & Security, and allow to "open anyway" the app.
  
For the next launch, you can open the app with a left click as usual.

At first start, on Windows and macOS, the app may take time to launch. The next launches will be significantly faster.

## Citation and License
By using the app, you agree to cite our paper if you use the app in a publication or research project. Please cite the following reference:

@article{...,
  title={Directed cortico-limbic dialogue in the human brain},
  author={Ellen van Maren, Camille G. Mignardot, Roland Widmer, Cecilia Friedrichs-Maeder, Päivi Nevalainen, Markus Fuchs, Juan Anso, Claudio Pollo, Athina Tzovara, Timothée Proix, Kaspar Schindler, Maxime O. Baud},
  journal={...},
  volume={...},
  number={...},
  pages={...},
  year={...},
  publisher={...}
}

Additionally, the app is made available under the following terms:
  - You may use the Connecto app for non-commercial purposes, including publications and research.
  - Any use of the app in a publication, research, or academic work must include proper attribution, specifically citing the above-mentioned paper.
  - Redistribution or commercial use of the app is not permitted without prior permission.
    
For any questions regarding the license or usage, please contact us at maxime.baud(at)insel.ch.

