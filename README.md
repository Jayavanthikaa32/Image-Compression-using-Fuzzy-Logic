# Image-Compression-using-Fuzzy-Logic

# Image compression 

Image compression is the technique used to decrease the size of an image while preserving its visual quality. It involves eliminating unnecessary data to optimize storage, transmission, or processing of images without compromising their visual integrity.

# Image compression using Fuzzy logic 

In image compression, fuzzy logic is utilised to reflect the subjective character of human perception, resulting in a more accurate representation of picture quality. By using fuzzy membership functions, fuzzy logic is utilised in image compression to analyse and adaptively alter the amount of compression applied to different regions of an image based on their perceived value or visual significance. This enables a more flexible and subjective approach to compression, maintaining important features while eliminating less important information.

# This project compares the image compression with fuzzy logic and without fuzzy logic.

# Steps in Image compression using fuzzy logic 

Preprocessing: Techniques such as colour space transformation, downsampling, and filtering are used to prepare the picture for compression.

Transformation: Image data is changed from one domain to another using techniques such as Discrete Cosine Transform (DCT). This transformation aids in the consolidation of picture energy into fewer coefficients.

Quantization : It is the process of lowering the accuracy or range of values of changed coefficients. This phase adds information loss by decreasing the precision of the converted coefficients.

### In the quantization stage of image compression, fuzzy logic is commonly utilised. It is used to establish the optimum amount of quantization for various image components depending on their perceived value or visual significance. Because fuzzy logic takes into account the subjective nature of human perception, it aids in maintaining key features while lowering less crucial information, resulting in increased image quality following compression.

Encoding: The quantized coefficients are encoded using a variety of techniques, including Huffman coding, Arithmetic coding, and Run-Length Encoding. This stage minimises the amount of the encoded data by using shorter codes to represent common patterns or symbols.

Decoding involves reversing the encoding process and recovering the quantized coefficients from the encoded data.

The reconstructed coefficients are translated back to the spatial domain using the inverse of the transformation used in step 2.

Postprocessing: To improve the visual quality of the reconstructed image, postprocessing techniques such as filtering, upsampling, and colour space conversion may be used.
