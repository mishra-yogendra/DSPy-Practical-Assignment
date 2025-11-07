graph TD
  ambient_temperature["ambient temperature<br/><i>Concept</i>"]
  thermoregulation["thermoregulation<br/><i>Concept</i>"]
  heat_waves["heat waves<br/><i>Concept</i>"]
  cold_winter_spells["cold winter spells<br/><i>Concept</i>"]
  malnutrition["malnutrition<br/><i>Concept</i>"]
  carbon_footprint["carbon footprint<br/><i>Concept</i>"]
  urban_planning["urban planning<br/><i>Method</i>"]
  reduction_in_energy_consumption["reduction in energy consumption<br/><i>Method</i>"]
  climate_change["climate change<br/><i>Concept</i>"]
  air_pollution["air pollution<br/><i>Concept</i>"]
  greenhouse_effect["greenhouse effect<br/><i>Concept</i>"]
  respiratory_disease["respiratory disease<br/><i>Disease</i>"]
  cardiovascular_disease["cardiovascular disease<br/><i>Disease</i>"]
  vectorborne_diseases["vector-borne diseases<br/><i>Disease</i>"]
  waterborne_diseases["waterborne diseases<br/><i>Disease</i>"]
  foodborne_diseases["foodborne diseases<br/><i>Disease</i>"]
  mental_health_problems["mental health problems<br/><i>Concept</i>"]
  allergies["allergies<br/><i>Concept</i>"]
  elderly["elderly<br/><i>Demographic</i>"]
  infants["infants<br/><i>Demographic</i>"]
  vulnerable_groups["vulnerable groups<br/><i>Concept</i>"]
  primary_producers["primary producers<br/><i>Concept</i>"]
  livestock["livestock<br/><i>Concept</i>"]
  carbon_dioxide["carbon dioxide<br/><i>Chemical</i>"]
  methane["methane<br/><i>Chemical</i>"]
  nitrous_oxide["nitrous oxide<br/><i>Chemical</i>"]
  ocean_acidification["ocean acidification<br/><i>Concept</i>"]
  ozone_depletion["ozone depletion<br/><i>Concept</i>"]
  adaptation["adaptation<br/><i>Concept</i>"]
  acclimatization["acclimatization<br/><i>Concept</i>"]
  epidemiological_studies["epidemiological studies<br/><i>Method</i>"]
  public_health_measures["public health measures<br/><i>Method</i>"]
  mortality["mortality<br/><i>Concept</i>"]
  ambient_temperature -- "affects" --> mortality
  heat_waves -- "increases" --> mortality
  cold_winter_spells -- "increases" --> mortality
  urban_planning -- "reduces" --> carbon_footprint
  reduction_in_energy_consumption -- "reduces" --> carbon_footprint
  climate_change -- "increases" --> air_pollution
  air_pollution -- "exacerbates" --> respiratory_disease
  air_pollution -- "exacerbates" --> cardiovascular_disease
  vulnerable_groups -- "are affected by" --> climate_change
  elderly -- "are part of" --> vulnerable_groups
  infants -- "are part of" --> vulnerable_groups
  carbon_dioxide -- "contributes to" --> greenhouse_effect
  methane -- "contributes to" --> greenhouse_effect
  nitrous_oxide -- "contributes to" --> greenhouse_effect
  ocean_acidification -- "is caused by" --> climate_change
  ozone_depletion -- "is caused by" --> climate_change
