# dx11UberShaderBlendND
Custom DX11Shader with Normal and Displacement Map Blending for Autodesk Maya.
This dx11Shader is used for creating wrinkle effects in my personal rigging project, you may check out at this website: https://vimeo.com/127718381 
This custom shader is based on orignal AutodeskUberShader which Maya ships.

You can load 'uberShaderBlendND.fx' using dx11Shader, after loading then there is two new columns for Normal Maps and Displacement Maps.
Normal/Displacement Map 1 is the base. Normal/Displacement Map 2 - 30 contain a toggle attribute, mask map and blending attrbute called 'Mask Mul'.

Thanks to mq for the very first coding and testing.
