# UnityStandardShaderVertexColor
A version of Unity's "Standard Shader" with support for per-vertex color

This should hopefully be the definitive repository for Unity3d users looking to use the standard shader with meshes that have vertex colors. This shader supports everything the stock "Standard Shader" does, with addition of a new material option that multiplies vertex colors by the material's albedo color. That means this shader allows the use of vertex colors in conjunction with all the great built-in features of the standard shader, including alpha support, instancing, shadows, meta probe info and more!

Why use per-vertex colors? It allows you to re-use the same material for many meshes in your scene, which will allow them to be batch rendered or instanced with very little overhead. Also you get to have that sweet, indie low-poly look for free!
