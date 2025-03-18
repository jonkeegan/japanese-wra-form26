# japanese-wra-form26
A script to parse the National Archives' data file containing detailed data about the incarcerated people held in "internment camps" in the US between 1942 and 1946

## processed.csv
This is the outoput of the Python script. 

### Columns:

<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: left;">
      <th>Column</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
<tr><td><stong>last_name</strong></td><td>Lasdt name</td></tr>
<tr><td><stong>first_name</strong></td><td>First name</td></tr>
<tr><td><stong>middle_initial</strong></td><td>Middle initial</td></tr>
<tr><td><stong>relocation_center</strong></td><td>Relocation center</td></tr>
<tr><td><stong>assembly_center</strong></td><td>Assembly center</td></tr>
<tr><td><stong>previous_address</strong></td>Previous address code<td></td></tr>
<tr><td><stong>country_of_birth</strong></td><td>Country of birth code</td></tr>
<tr><td><stong>fathers_occupation_in_us</strong></td><td>Father's occupation in US code</td></tr>
<tr><td><stong>fathers_occupation_abroad</strong></td><td>Father's occupation abroad code</td></tr>
<tr><td><stong>total_years_schooling_japan</strong></td><td>Total years schooling in Japan code</td></tr>
<tr><td><stong>years_schooling_in_japan_during</strong></td><td>Years schooling in Japan during...(code)</td></tr>
<tr><td><stong>major_subject</strong></td><td>Major subject (code)</td></tr>
<tr><td><stong>year_first_arrival_us_foreign_born</strong></td><td>Year first arrival in US (foreign born) (code)</td></tr>
<tr><td><stong>total_time_in_japan</strong></td><td>Total time in Japan (code)</td></tr>
<tr><td><stong>number_times_in_japan</strong></td><td>Number of times in Japan</td></tr>
<tr><td><stong>age_at_time_in_japan</strong></td><td>Age at time in Japan</td></tr>
<tr><td><stong>military_service_pensions_defects</strong></td><td>Military or naval service, No public assistance or Pensions, No uncorrected major physical defects</td></tr>
<tr><td><stong>file_number</strong></td><td>Individual (file) number</td></tr>
<tr><td><stong>sex_marital_status</strong></td><td>Sex and marital status (code)</td></tr>
<tr><td><stong>race_individual_and_spouse</strong></td><td>Race, individual and spouse (code)</td></tr>
<tr><td><stong>year_of_birth</strong></td><td>Year of birth</td></tr>
<tr><td><stong>birthplace</strong></td><td>Birthplace (code)</td></tr>
<tr><td><stong>alien_reg_ssn_japanese_lang_school</strong></td><td>Alien registration No., Social security No., and Japanese Language School (code)</td></tr>
<tr><td><stong>highest_grade_completed</strong></td><td>Highest grade completed or grade attending</td></tr>
<tr><td><stong>language</strong></td><td>Language (code)</td></tr>
<tr><td><stong>religion</strong></td><td>Religion (code)</td></tr>
<tr><td><stong>place_of_birth_lookup</strong></td><td>Place of birth (matched to code)</td></tr>
<tr><td><stong>relocation_center_lookup</strong></td><td>Relocation center (matched to code)</td></tr>
<tr><td><stong>assembly_center_lookup</strong></td><td>Assembly center (matched to code)</td></tr>
<tr><td><stong>country_of_birth_lookup</strong></td><td>Country of birth (matched to code)</td></tr>
<tr><td><stong>race_individual_and_spouse_lookup</strong></td><td>Race, individual and spouse (matched to code)</td></tr>
<tr><td><stong>language_lookup</strong></td><td>Language (matched to code)</td></tr>
<tr><td><stong>sex_marital_status_lookup</strong></td><td>Marital status (matched to code)</td></tr>
<tr><td><stong>file_number_base</strong></td><td>File number base (Families shared a 5 digit file number, each family member was assigned a letter at the end of the file number. Ex: 12345A, 12345B...</td></tr>
<tr><td><stong>previous_address_state_county</strong></td><td>Previous address state and county</td><td>Not implemented yet<td></tr>
 </tbody>
</table>
