# 1568346_20220619

> - "1568346_20220619"?
>   - "1568346"?
>     - "Q3133368"
>       - https://www.wikidata.org/wiki/Q3133368
>         - /repository - data storage for software revision control/@eng-Latn
>   - "20220619"?
>     - 2022-20-19

<!--
Ignore this, just for Rocha tests dealing with file permissions

cd /workspace/git/mdciii/1568346_20220619
sudo chown 1000:1603 -R officina/
sudo chmod 1775 -R officina/
sudo find officina/ -type f -exec chmod 644 -- {} +

sudo su mdciii
source ~/.profile

# Protege
#    /opt/Protege-5.5.0/run.sh


### Other tests ----------------------------------------------------------------

./999999999/0/999999999_54872.py --objectivum-formato=_temp_no1 /workspace/git/mdciii/1568346_20220619/officina/1603/16/24/1/1603_16_24_1.no1.tm.hxl.csv --rdf-sine-spatia-nominalibus=devnull --rdf-trivio=5001

./999999999/0/999999999_54872.py --objectivum-formato=_temp_hxl_meta_in_json /workspace/git/mdciii/1568346_20220619/officina/1603/16/24/1/1603_16_24_1.no1.tm.hxl.csv --rdf-sine-spatia-nominalibus=devnull --rdf-trivio=5001 | jq

./999999999/0/999999999_54872.py --objectivum-formato=_temp_hxl_meta_in_json --punctum-separato-de-fontem=$'\t' /workspace/git/EticaAI/lexicographi-sine-finibus/officina/999999999/1568346/data/cod-ab-example1-with-inferences.no1.hxl.tm.tsv --rdf-sine-spatia-nominalibus=devnull --rdf-trivio=5001 | jq

# The next one works; no1.hxl.tm.tsv test case on lsf is out of sync at the moment

./999999999/0/999999999_54872.py --objectivum-formato=_temp_bcp47_meta_in_json --punctum-separato-de-fontem=$'\t' /workspace/git/EticaAI/lexicographi-sine-finibus/officina/999999999/1568346/data/cod-ab-example1-with-inferences.bcp47.tsv --rdf-sine-spatia-nominalibus=devnull --rdf-trivio=5001 | jq

vartest1=$(head -n 1 /workspace/git/EticaAI/lexicographi-sine-finibus/officina/999999999/1568346/data/cod-ab-example1-with-inferences.bcp47.tsv)
./999999999/0/999999999_54872.py --objectivum-formato=_temp_header_bcp47_to_hxl "$vartest1"


-->
