FROM tensorflow:latest-devel-gpu

ADD def_classify.py
ADD classify_using_coordinates.py
ADD retrained_graph-4_4N_5_7.pb
ADD retrained_labels-4_4N_5_7.txt

# mount-point for persistence beyond container
VOLUME ["/data"]
