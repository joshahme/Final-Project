# Final-Project
Protein Amino Acid Sequence

> # Set the working directory to the root of your package
> setwd("C:/Users/Joshah/OneDrive/Desktop/ProteinAminoAcidSequence")
> 
> # Build and install the package
> devtools::install()
> > # Load the package
> library(ProteinAminoAcidSequence)
> 
> # Test the functions
> calculate_molecular_weight("MVHLTPEEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLDNLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH")
[1] 15979.91
> protein_amino_seq("MVHLTPEEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLDNLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH")
[1] "MVHLTPEEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLDNLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH"
> 
> # Test the functions with insulin protein sequence
> insulin_sequence <- "MALWMRLLPLLALLALWGPDPAAAFVNQHLCGSHLVEALYLVCGERGFFYTPKTRREAEDLQVGQVELGGGPGAGSLQPLALEGSLQKRGIVEQCCTSICSLYQLENYCN"
> insulin_molecular_weight <- calculate_molecular_weight(insulin_sequence)
> insulin_amino_seq <- protein_amino_seq(insulin_sequence)
> 
> # Print the results
> print(paste("Insulin Molecular Weight:", insulin_molecular_weight))
[1] "Insulin Molecular Weight: 11962.44"
> print(paste("Insulin Amino Acid Sequence:", insulin_amino_seq))
[1] "Insulin Amino Acid Sequence: MALWMRLLPLLALLALWGPDPAAAFVNQHLCGSHLVEALYLVCGERGFFYTPKTRREAEDLQVGQVELGGGPGAGSLQPLALEGSLQKRGIVEQCCTSICSLYQLENYCN"
> 
> # Test the functions with albumin protein sequence
> albumin_sequence <- "MKWVTFISLLFLFSSAYSRGVFRRDAHKSEVAHRFKDLGEENFKALVLIAFAQYLQQCPFEDHVKLVNEVTEFAKTCVADESAENCDKSLHTLFGDKLCTVATLRETYGEMADCCAKQEPERNECFLQHKDDNPNLPRLVRPEVDVMCTAFHDNEETFLKKYLYEIARRHPYFYAPELLFFAKRYKAAFTECCQAADKAACLLPKLDELRDEGKASSAKQRLKCASLQKFGERAFKAWAVARLSQRFPKAEFAEVSKLVTDLTKVHTECCHGDLLECADDRADLAKYICENQDSISSKLKECCEKPLLEKSHCIAEVENDEMPADLPSLAADFVESKDVCKNYAEAKDVFLGMFLYEYARRHPDYSVVLLLRLAKTYETTLEKCCAAADPHECYAKVFDEFKPLVEEPQNLIKQNCELFEQLGEYKFQNALLVRYTKKVPQVSTPTLVEVSRNLGKVGSKCCKHPEAKRMPCAEDYLSVVLNQLCVLHEKTPVSDRVTKCCTESLVNRRPCFSALTPDETYVPKAFDEKLFTFHADICTLPDTEKQIKKQTALVELLKHKPKATEEQLKTVMENFVAFVDKCCAADDKEACFAVEGPKLVVSTQTALA"
> albumin_molecular_weight <- calculate_molecular_weight(albumin_sequence)
> albumin_amino_seq <- protein_amino_seq(albumin_sequence)
> 
> # Print the results
> print(paste("Albumin Molecular Weight:", albumin_molecular_weight))
[1] "Albumin Molecular Weight: 69181.53"
> print(paste("Albumin Amino Acid Sequence:", albumin_amino_seq))
[1] "Albumin Amino Acid Sequence: MKWVTFISLLFLFSSAYSRGVFRRDAHKSEVAHRFKDLGEENFKALVLIAFAQYLQQCPFEDHVKLVNEVTEFAKTCVADESAENCDKSLHTLFGDKLCTVATLRETYGEMADCCAKQEPERNECFLQHKDDNPNLPRLVRPEVDVMCTAFHDNEETFLKKYLYEIARRHPYFYAPELLFFAKRYKAAFTECCQAADKAACLLPKLDELRDEGKASSAKQRLKCASLQKFGERAFKAWAVARLSQRFPKAEFAEVSKLVTDLTKVHTECCHGDLLECADDRADLAKYICENQDSISSKLKECCEKPLLEKSHCIAEVENDEMPADLPSLAADFVESKDVCKNYAEAKDVFLGMFLYEYARRHPDYSVVLLLRLAKTYETTLEKCCAAADPHECYAKVFDEFKPLVEEPQNLIKQNCELFEQLGEYKFQNALLVRYTKKVPQVSTPTLVEVSRNLGKVGSKCCKHPEAKRMPCAEDYLSVVLNQLCVLHEKTPVSDRVTKCCTESLVNRRPCFSALTPDETYVPKAFDEKLFTFHADICTLPDTEKQIKKQTALVELLKHKPKATEEQLKTVMENFVAFVDKCCAADDKEACFAVEGPKLVVSTQTALA"
> 
> # Load the package if not already loaded
> if (!requireNamespace("ProteinAminoAcidSequence", quietly = TRUE)) {
+     install.packages("ProteinAminoAcidSequence")
+ }
> library(ProteinAminoAcidSequence)
> 
> # Amino acid sequence of thyroxine (T4)
> thyroxine_sequence <- "Glu-His-Pro-Ile-Gly-Tyr-Met-Ile-Gln-Ser-Tyr-Thr-Asn-Thr-Cys-Arg-Ser-Cys"
> 
> # Calculate the molecular weight
> molecular_weight_thyroxine <- calculate_molecular_weight(thyroxine_sequence)
> 
> # Print the result
> print(molecular_weight_thyroxine)
[1] NA
> 
> # Load the package if not already loaded
> if (!requireNamespace("ProteinAminoAcidSequence", quietly = TRUE)) {
+     install.packages("ProteinAminoAcidSequence")
+ }
> library(ProteinAminoAcidSequence)
> 
> # Amino acid sequence of thyroxine (T4)
> thyroxine_sequence <- "Glu-His-Pro-Ile-Gly-Tyr-Met-Ile-Gln-Ser-Tyr-Thr-Asn-Thr-Cys-Arg-Ser-Cys"
> 
> # Calculate the molecular weight
> molecular_weight_thyroxine <- calculate_molecular_weight(thyroxine_sequence)
> 
> # Print the result
> print(molecular_weight_thyroxine)
[1] NA
