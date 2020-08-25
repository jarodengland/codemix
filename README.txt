source: https://wiki.eclipse.org/Equinox_p2_Repository_Mirroring

eclipsec.exe -nosplash -verbose -application org.eclipse.equinox.p2.metadata.repository.mirrorApplication -source http://genuitec.com/updates/codemix/ci/ -destination file:C:\codemix

eclipsec.exe -nosplash -verbose -application org.eclipse.equinox.p2.artifact.repository.mirrorApplication -source http://genuitec.com/updates/codemix/ci/ -destination file:C:\codemix