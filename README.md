# hacs_waste_collection_static_source_chambly_QC
Static source for HACS waste_collection for Chambly with Home Assistant

You need to install HACS Waste Collection to your Home Assistant, please follow [Installation and Configuration](https://github.com/mampfes/hacs_waste_collection_schedule?tab=readme-ov-file#installation-and-configuration)

## Instructions

Copy the collectes_ouest.yaml or collectes_est.yaml depending on your location in the city, to your collectes folder.

If you didn't configure a collectes folder before, follow these steps:

1. Add these lines in your configuration.yaml :

> #waste_collection: <BR>
> &nbsp;&nbsp;waste_collection_schedule: !include_dir_named custom_components/waste_collection_schedule/collectes

2. Create the "collectes" folder in /config/custom_components/waste_collection_schedule" folder in Home Assistant.
3. Download or copy the collectes_ouest.yaml or collectes_est.yaml file in your /config/custom_components/waste_collection_schedule/collectes folder.
4. Reboot HA

## Creat sensor

