> Ελληνικά: Μηχανική μετάφραση της έγκυρης αγγλικής πηγής. Οι διορθώσεις στη μητρική γλώσσα είναι ευπρόσδεκτες. [αγγλικός](../../README.md) | [Όλες οι γλώσσες](../README.md)

# Εργαλεία, μοντέλα και πηγές

![Εργαλεία, μοντέλα, σύνολα δεδομένων, εκδόσεις και ρόλοι που διατηρούνται σε ένα ελεγχόμενο μητρώο πηγών](../../assets/tool-model-source-index.png)

Κάθε κύριο εξωτερικό εργαλείο ή μοντέλο που κατονομάζεται από το συντηρούμενο καθολικό του Datacenter συνδέεται εδώ με την επίσημη δημόσια σελίδα έργου ή διανομής του. Αυτός είναι ένας δείκτης άμεσης εξάρτησης και μοντέλου, όχι ένας μεταβατικός λογαριασμός υλικών λογισμικού.

Η στήλη κατάστασης περιγράφει τη σχέση που καταγράφεται για το στοιχείο. Ένα εργαλείο που έχει αποσυρθεί ή επιθεωρηθεί παραμένει πιστωμένο χωρίς να παρουσιάζεται ως τρέχων κωδικός χρόνου εκτέλεσης.

Ένα εξωτερικό μοντέλο που ονομάζεται σε ένα πείραμα δεν είναι επίσης το σύστημα εγγραφής. Ο ρόλος του περιορίζεται στο ωφέλιμο φορτίο και τη λειτουργία που τεκμηριώνεται για αυτό το πείραμα. Ακόμα κι αν ο παραλήπτης διατηρεί τα παρεχόμενα byte, το παραλειπόμενο σώμα, η προέλευση, το χρονικό ιστορικό και ο μηχανισμός κατασκευής ωφέλιμου φορτίου παραμένουν εκτός αυτής της εξάρτησης.

| Εργαλείο ή μοντέλο | Επίσημη δημόσια πηγή | Καταγεγραμμένη σχέση | Χρησιμοποιείται από |
|---|---|---|---|
| Μοντέλο AMF ARI RoBERTa OpenVINO | [πηγή](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | αντίθετα στο ρεύμα | amf_ari, argument_relation_classifier |
| BlingFire | [πηγή](https://github.com/microsoft/BlingFire) | αντίθετα στο ρεύμα | microplanner, slop_analysis |
| Κουτί | [πηγή](https://github.com/caddyserver/caddy) | αντίθετα στο ρεύμα | tls |
| Απεσταλμένος | [πηγή](https://github.com/envoyproxy/envoy) | συνταξιούχος προκάτοχος (όχι χρόνο εκτέλεσης) | δρομολογητή |
| FactCG | [πηγή](https://github.com/derenlei/FactCG) | αντίθετα στο ρεύμα | semantic_observer |
| FastAPI | [πηγή](https://github.com/fastapi/fastapi) | αντίθετα στο ρεύμα | συνομιλία_διαχωριστής, αποστολή_ελέγχου, δρομολογητής |
| FastCoref | [πηγή](https://github.com/shon-otmazgin/fastcoref) | αντίθετα στο ρεύμα | προεπεξεργασία λόγου |
| faster-distil-whisper-large-v3 | [πηγή](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | αντίθετα στο ρεύμα | ομιλίες |
| πιο γρήγορα-ψιθύρισε | [πηγή](https://github.com/SYSTRAN/faster-whisper) | αντίθετα στο ρεύμα | ομιλίες |
| Γραφβίζ | [πηγή](https://gitlab.com/graphviz/graphviz) | αντίθετα στο ρεύμα | αποστολή_ελέγχου |
| IsaNLP RST | [πηγή](https://github.com/tchewik/isanlp_rst) | αντίθετα στο ρεύμα | προεπεξεργασία λόγου |
| γόνατο | [πηγή](https://github.com/arvkevi/kneed) | αντίθετα στο ρεύμα | collapse_packets |
| LibreChat | [πηγή](https://github.com/danny-avila/LibreChat) | αντίθετα στο ρεύμα | κουβέντα |
| MiniCheck | [πηγή](https://github.com/Liyan06/MiniCheck) | αντίθετα στο ρεύμα | semantic_observer |
| MongoDB | [πηγή](https://github.com/mongodb/mongo) | αντίθετα στο ρεύμα | mongodb |
| NetworkX | [πηγή](https://github.com/networkx/networkx) | αντίθετα στο ρεύμα | graph_projection |
| NLTK | [πηγή](https://github.com/nltk/nltk) | αντίθετα στο ρεύμα | slop_analysis |
| Node.js | [πηγή](https://github.com/nodejs/node) | αντίθετα στο ρεύμα | κουβέντα |
| Nomic Embed Text | [πηγή](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | αντίθετα στο ρεύμα | olama_embed |
| Ολάμα | [πηγή](https://github.com/ollama/ollama) | αντίθετα στο ρεύμα | olama, olama_embed |
| OpenVINO | [πηγή](https://github.com/openvinotoolkit/openvino) | αντίθετα στο ρεύμα | amf_ari |
| pgvector | [πηγή](https://github.com/pgvector/pgvector) | αντίθετα στο ρεύμα | postgres |
| PostgreSQL | [πηγή](https://github.com/postgres/postgres) | αντίθετα στο ρεύμα | postgres |
| ψουτίλ | [πηγή](https://github.com/giampaolo/psutil) | αντίθετα στο ρεύμα | hardware_telemetry |
| Psycopg | [πηγή](https://github.com/psycopg/psycopg) | αντίθετα στο ρεύμα | αποστολή_ελέγχου |
| Qwen3 | [πηγή](https://github.com/QwenLM/Qwen3) | αντίθετα στο ρεύμα | όλαμα, vllm |
| Spay | [πηγή](https://github.com/explosion/spaCy) | αντίθετα στο ρεύμα | microplanner, slop_analysis, surface_realizer |
| Ομιλίες | [πηγή](https://github.com/speaches-ai/speaches) | αντίθετα στο ρεύμα | ομιλίες |
| stable-diffusion.cpp | [πηγή](https://github.com/leejet/stable-diffusion.cpp) | αντίθετα στο ρεύμα | εικών |
| submodlib | [πηγή](https://github.com/decile-team/submodlib) | αντίθετα στο ρεύμα | collapse_packets |
| Μετασχηματιστές | [πηγή](https://github.com/huggingface/transformers) | αντίθετα στο ρεύμα | semantic_observer |
| Vikunja | [πηγή](https://github.com/go-vikunja/vikunja) | αντίθετα στο ρεύμα | vikunja |
| vLLM | [πηγή](https://github.com/vllm-project/vllm) | αντίθετα στο ρεύμα | vllm |
| vLLM Semantic Router | [πηγή](https://github.com/vllm-project/semantic-router) | συνταξιούχος προκάτοχος / επιθεωρημένη καταγωγή (όχι χρόνος εκτέλεσης) | δρομολογητή |
| Z-Image-Turbo | [πηγή](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | αντίθετα στο ρεύμα | εικών |
| Αναφορά συσκευασίας Z-Image-Turbo-Windows | [πηγή](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | επιθεωρημένη αναφορά συσκευασίας (όχι διεπαφή χρήστη χρόνου εκτέλεσης) | εικών |

## Όριο διανομής

Η δημόσια τεκμηρίωση δεν περιέχει κανένα καταχωρημένο κωδικό ή βάρη μοντέλου έργου. Μια μελλοντική διανομή λογισμικού πρέπει να δημιουργήσει ακριβείς εκδόσεις, αναθεωρήσεις, κατακερματισμούς, μεταβατικές εξαρτήσεις, όρους μοντέλου και κείμενα άδειας από τα byte που πραγματικά διανέμονται. Ένας σύνδεσμος έργου είναι η απόδοση και η ιχνηλασιμότητα, όχι μια γνώμη άδειας χρήσης.
