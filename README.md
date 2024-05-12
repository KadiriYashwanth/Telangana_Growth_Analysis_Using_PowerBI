# Telangana_Growth_Analysis_Using_PowerBI

## Performed an extensive analysis of three pivotal datasets, providing valuable insights into Telangana's development trajectory across various sectors.

1.Stamp Analysis:
                Conducted in-depth analysis of Document Registration and E-Stamp Challan data, identifying top 5 registered documents and E-Stamp Challans by district. Conducted trend analysis over the past 5 years, offering valuable perspectives for efficient governance and regulatory enhancement.

2.Telangana Transportation Analysis:
                                   Analyzed top 5 most selling vehicle types (electric, petrol, diesel) and models (motorcycle, agriculture, motorcar) by district, crucial for infrastructure planning and economic development.

3.Telangana iPass Investment Sector Analysis: 
                                           Identified top 5 investments by sector and district, highlighting potential sectors and districts for investment, providing strategic directions for economic prosperity and job creation.

This analysis demonstrates my ability to derive actionable insights from complex datasets, offering valuable strategic guidance for policymakers, investors, and stakeholders.

 
 
from pdf2image import convert_from_path

 
pdf_path =  'https://1drv.ms/b/c/3a385a8883f3623d/EY45ew2KeLpItmn4SP-t0fEByW_klHCB1UYFiXELVQoaFQ?e=pXJvyU'

 
images = convert_from_path(pdf_path)

for i, image in enumerate(images):
    image.save(f'page_{i+1}.png', 'PNG')


