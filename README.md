Hadoop-MapReduce-JSON
=====================

Given the input author-book tuples, map-reduce program procudes a JSON object which contains all the books from same author in a JSON array

The program uses a combiner to minimize number of key-value pairs generated
from each node.


Part of he output file:


{"author":"Pu. Bhā Bhāve","books":"[{"book":"Viṡrāntī"},{"book":"Asaṅgāśī saṅga"}]"}
{"author":"Pu. La Kulakarṇī","books":"[{"book":"Puṇyāce Gaṇapati"}]"}
{"author":"Puangkram C. Schmitz","books":"[{"book":"Practical Thai cooking"}]"}
{"author":"Public Archives of Canada","books":"[{"book":"Union list of manuscripts in Canadian repositories, Supplement .."},{"book":"Guide to Canadian ministries since Confederation"},{"book":"Centennial issues of Canadian newspapers"},{"book":"INITIAL BIBLIOGRAPHY OF PRINCE ALBERT NATIONAL PARK"},{"book":"REPRODUCTION SERVICES OF THE PUBLIC ARCHIVES OF CANADA"}]"}
{"author":"Public Archives of Canada.","books":"[{"book":"Public Archives of Canada ="},{"book":"Preliminary inventory; record group 10, Indian Affairs"},{"book":"Union list of manuscripts in Canadian repositories"},{"book":"Catalogue of pamphlets in the Public Archives of Canada"},{"book":"Répertoire des recensements du Québec, 1825-1871"},{"book":"List of publications of the Public Archives of Canada ="}]"}
{"author":"Public Archives of Canada. Public Records Division.","books":"[{"book":"Records of the Centennial Commission of Canada (RG 69) ="}]"}
{"author":"Public Enemy (Musical group)","books":"[{"book":"Public Enemy"}]"}
