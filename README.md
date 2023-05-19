foamInstallationTest
mkdir -p $FOAM_RUN
cd $FOAM_RUN
cp -r $FOAM_TUTORIALS/incompressible/simpleFoam/pitxDaily ./
cd pitzDaily
blockmesh
simpleFoam
