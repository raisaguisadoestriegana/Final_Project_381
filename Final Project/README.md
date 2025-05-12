# Modeling Radiation Therapy Dose Deposition

This project will simulate how radiation intensity decreases as it penetrates different tissue types. I will use the Beer–Lambert Law to compare soft tissue and bone attenuation. By plotting the results, I will visually show how dense material attenuates and absorbs radiation faster. 

## Physics Equations
Beer–Lambert Law (Decay):

**I(x) = I₀ × exp(-μx)**

Where:
- *I(x)* = intensity at depth *x*
- *I₀* = surface intensity
- *μ* = attenuation coefficient (cm⁻¹)
- *x* = depth (cm)

Typical μ values:
- Lung: ~0.03 cm⁻¹  
- Soft tissue: ~0.15 cm⁻¹  
- Bone: ~0.30 cm⁻¹