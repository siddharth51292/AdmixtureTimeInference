`averaged_mf.simmap` generated by `awk 'NR>1 {print ,,( + )/2 ; }' /fs/cbsubscb09/storage/resources/genetic_maps/refined_mf.simmap | sed -e '1i#chr pos sex_avg\' > averaged_mf.simmap` && `sed -i 's/ /\t/g' averaged_mf.simmap`
`admixture-times.def` contains deffile information to generate pedigrees with 1-4 inherited meioses from ped-sim 