#!/bin/bash
BaseDir=/media/d3c21c66-af4b-41d4-b098-462e83fa641d/Serien/
ShortBD=/ln/target
DownloadFolderEN=/opt/SABnzbd/Downloads/complete
DownloadFolderDE=/opt/SABnzbd2/Downloads/complete
LockFile=/home/pyload/.pyload/filebot.lock
Serie="{n.replaceAll(/[!?.]+\$/).replaceAll(/[\`´‘’ʻ]/, \"'\").replace(':',' -')}"
Titel="{t.replaceAll(/[!?.]+\$/).replaceAll(/[\`´‘’ʻ]/, \"'\")}"



#count=`find "$DownloadFolder" -name "*.rar" -o -name "*.r0*" -o -name "*.zip" 2>/dev/null | wc -l`
#if [ $count != 0 ]
#then
#	echo "Abbruch, hier sind noch Archive..."
#	exit
#else
#	return 0

#moveen(){
	filebot -rename "$DownloadFolderEN" --db thetvdb --format "$ShortBD/Englisch/$Serie/Staffel {s} EN {vf}/$Serie - {s00e00} - $Titel" -non-strict -r
#}
#movede(){
#	filebot -rename "$DownloadFolderDE" --db thetvdb --format "$ShortBD/Deutsch/$Serie/Staffel {s} DE + EN {vf}/$Serie - {s00e00} - $Titel" -non-strict -r
#}

#ls | grep ENGLISCH | while read i; do moveen; done
#ls | grep DEUTSCH | while read i; do movede; done

#slink(){
#	cp -rsv /ln/test/
#}

#find $BaseDir -type f | grep -v 'DE' | while read i; do ln -s -- "$i" "/ln/test"/{} ; done

#TargetDir=/ln/test

#cd $BaseDir

#find "$BaseDir" -type d -exec mkdir --parents -- "$TargetDir"{} \;

#find "$BaseDir" -type f -exec grep -v 'DE' {} \; -exec  ln -s "$BaseDir"{} "$TargetDir"{} \;

exit


#find /media/d3c21c66-af4b-41d4-b098-462e83fa641d/Serien/Split\ Me/ -not -type d | grep -v 'DE'
