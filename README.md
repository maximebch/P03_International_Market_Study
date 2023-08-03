# P03_International_Market_Study
<h2><strong><em>Data Analyst Certification by OpenClassrooms, in partnership with&nbsp;ENSAE-ENSAI</em></strong></h2>
<p><em>Analyzing foreign markets for exportation</em></p>
<p><em>Skills:</em></p>
<ul>
    <li style="font-style: italic;"><em>Interpret a PCA</em></li>
    <li style="font-style: italic;"><em>Construct and read a dendogram</em></li>
    <li style="font-style: italic;"><em>Test the adequacy to a law by a statistical test</em></li>
</ul>
<p><br></p>
<div>
    <div>
        <div>
            <div>
                <h1>Produisez une &eacute;tude de march&eacute;</h1>
            </div>
        </div>
    </div>
    <div><br></div>
</div>
<h3>Pr&eacute;requis</h3>
<p>Pour effectuer ce projet, vous devrez ma&icirc;triser la manipulation de donn&eacute;es en&nbsp;<strong>Python</strong> ou&nbsp;<strong>R</strong>, appliquer ces langages &agrave; la&nbsp;<strong>statistique descriptive</strong> ainsi qu&apos;&agrave; la&nbsp;<strong>classification automatique</strong>.</p>
<p>&nbsp;</p>
<h3>Sc&eacute;nario</h3>
<p>Votre entreprise d&apos;agroalimentaire souhaite se d&eacute;velopper &agrave; l&apos;international. Elle est sp&eacute;cialis&eacute;e dans...</p>
<p>&nbsp;</p>
<p><img src="https://user.oc-static.com/upload/2017/05/11/14945088000673_shutterstock_521042725.jpeg" alt=""></p>
<p>&nbsp;</p>
<p>... le poulet !</p>
<p>L&apos;international, oui, mais pour l&apos;instant, le champ des possibles est bien large : aucun pays particulier ni aucun continent n&apos;est pour le moment choisi. Tous les pays sont envisageables !</p>
<p>Votre objectif sera d&apos;aider &agrave; cibler plus particuli&egrave;rement certains pays, dans le but d&apos;approfondir ensuite l&apos;&eacute;tude de march&eacute;. Plus particuli&egrave;rement, l&apos;id&eacute;al serait de produire des &quot;groupes&quot; de pays, plus ou moins gros, dont on conna&icirc;t les caract&eacute;ristiques.</p>
<p>Dans un premier temps, la strat&eacute;gie est plut&ocirc;t d&apos;exporter les produits plut&ocirc;t que de produire sur place, c&apos;est-&agrave;-dire dans le(s) nouveau(x) pays cibl&eacute;(s).</p>
<h3>Les donn&eacute;es</h3>
<p>Vous vous souvenez de la FAO, dans l&apos;un de vos pr&eacute;c&eacute;dents projets ?&nbsp;Allez,&nbsp;<a href="http://www.fao.org/faostat/fr/#data">on y retourne</a> ! Vous connaissez d&eacute;j&agrave; l&apos;interface du site, &agrave; vous de retrouver les donn&eacute;es qui vous seront utiles pour le projet.</p>
<h3>Votre mission</h3>
<p>Pour identifier les pays propices &agrave; une insertion dans le march&eacute; du poulet, il vous a &eacute;t&eacute; demand&eacute; de cibler les pays. Il vous faudra &eacute;galement &eacute;tudier les r&eacute;gimes alimentaires de chaque pays, notamment en termes de prot&eacute;ines d&apos;origine animale et en termes de calories.</p>
<p>Construisez votre &eacute;chantillon contenant l&apos;ensemble des pays disponibles, chacun caract&eacute;ris&eacute; par ces variables :</p>
<ul>
    <li>diff&eacute;rence de population entre une ann&eacute;e ant&eacute;rieure (au choix) et l&apos;ann&eacute;e courante, exprim&eacute;e en pourcentage ;</li>
    <li>proportion de prot&eacute;ines d&apos;origine animale par rapport &agrave; la quantit&eacute; totale de prot&eacute;ines dans la disponibilit&eacute; alimentaire du pays ;</li>
    <li>disponibilit&eacute; alimentaire en prot&eacute;ines par habitant ;</li>
    <li>disponibilit&eacute; alimentaire en calories par habitant.</li>
</ul>
<p>Construisez un dendrogramme contenant l&apos;ensemble des pays &eacute;tudi&eacute;s, puis coupez-le afin d&apos;obtenir 5 groupes.</p>
<p>Caract&eacute;risez chacun de ces groupes selon les variables cit&eacute;s pr&eacute;c&eacute;demment, et facultativement selon d&apos;autres variables que vous jugerez pertinentes (ex : le PIB par habitant). Vous pouvez le faire en calculant la position des centro&iuml;des de chacun des groupes, puis en les commentant et en les critiquant au vu de vos objectifs.</p>
<p>Donnez une&nbsp;<em>courte</em> liste de pays &agrave; cibler, en pr&eacute;sentant leurs caract&eacute;ristiques. Un d&eacute;coupage plus pr&eacute;cis qu&apos;en 5 groupes peut si besoin &ecirc;tre effectu&eacute; pour cibler un nombre raisonnable de pays.&nbsp;</p>
<p>Visualisez vos &nbsp;partitions dans le premier plan factoriel obtenu par ACP.</p>
<p>Dans votre partition, vous avez obtenu des groupes distincts. V&eacute;rifiez donc qu&apos;ils diff&egrave;rent r&eacute;ellement. Pour cela, r&eacute;alisez les tests statistiques suivants :</p>
<ul>
    <li><strong>un test d&apos;ad&eacute;quation</strong> : parmi les 4 variables, ou parmi d&apos;autres variables que vous trouverez pertinentes, trouvez une variable dont la loi est normale ;</li>
    <li><strong>un test de comparaison de deux populations (dans le cas gaussien)</strong> : choisissez 2 clusters parmi ceux que vous aurez d&eacute;termin&eacute;. Sur ces 2 clusters, testez la variable gaussienne gr&acirc;ce &agrave; un test de comparaison.</li>
</ul>
<h3>Livrables</h3>
<ul>
    <li>Le&nbsp;<strong>dendrogramme</strong> dans un format image (.png ou .jpg).</li>
    <li>Le&nbsp;<strong>code</strong> Python ou R&nbsp;reprenant tous les &eacute;l&eacute;ments de l&apos;&eacute;nonc&eacute;.</li>
    <li>Un&nbsp;<strong>fichier CSV</strong> contenant la liste des pays ainsi que (pour chacun d&apos;entre eux) leur groupe que vous aurez d&eacute;termin&eacute; apr&egrave;s avoir d&eacute;coup&eacute; le dendrogramme.</li>
    <li>Un&nbsp;<strong>ficher CSV</strong> contenant les centro&iuml;des des groupes et leurs coordonn&eacute;es dans chacune des dimensions.</li>
    <li>Une&nbsp;<strong>pr&eacute;sentation</strong> sous forme de slides pour la soutenance.</li>
</ul>
<aside>
    <p>Pour faciliter votre passage au jury, d&eacute;posez sur la plateforme, dans un dossier nomm&eacute; &ldquo;<em>P5_nom_prenom</em>&rdquo;, tous les livrables du projet. Chaque livrable doit &ecirc;tre nomm&eacute; avec le num&eacute;ro du projet et selon l&apos;ordre dans lequel il appara&icirc;t, par exemple &ldquo;<em>P5_01_dendogramme</em>&rdquo;, &ldquo;<em>P5_02_code</em>&rdquo;, et ainsi de suite.</p>
</aside>
<h3>Soutenance</h3>
<p>La soutenance, d&apos;une dur&eacute;e de 30 minutes, &nbsp;se d&eacute;roule en 2 &eacute;tapes :</p>
<ol>
    <li>Dans un premier temps, un&nbsp;&eacute;valuateur&nbsp;jouera de votre responsable,&nbsp;qui vous a demand&eacute; une pr&eacute;sentation sur des &quot;slides&quot;.&nbsp;Rappelez en introduction les enjeux, expliquez dans le d&eacute;tail votre d&eacute;marche (sans avoir peur de rentrer dans les d&eacute;tails math&eacute;matiques), et pr&eacute;sentez vos r&eacute;sultats et recommandations. (20 minutes)</li>
    <li>Enfin, votre &eacute;valuateur reprendra pleinement son r&ocirc;le d&rsquo;&eacute;valuateur pendant 10 minutes pour que vous puissiez d&eacute;brieffer ensemble.</li>
</ol>
