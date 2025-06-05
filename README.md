## Persentase Komentar Positif dan Negatif | [Ujaran Minta-Minta](#ujaran-minta-minta--persentase--wordcloud) | [Wordcloud](#wordcloud--persentase--ujaran-minta-minta)
![Persentase](https://github.com/user-attachments/assets/6aadc20e-39eb-46a3-a96a-402c41f7f17b)

Tingginya komentar negatif tidak selalu berarti masyarakat memiliki pandangan negatif terhadap content creator tersebut. Ada beberapa kasus yang dapat menyebabkan jumlah prediksi komentar negatif yang tinggi.
1.   Model indoBERT yang tidak dilatih secara khusus untuk dataset yang digunakan.

      Melatih model dengan dataset yang sudah dilabeli sendiri akan meningkatkan kemampuan model dalam melabeli kalimat yang tidak memiliki sentimen yang jelas dan membutuhkan konteks lebih. Misalnya kalimat-kalimat berikut:

      *   Bau uangnya kuat nih.
      *   Wow pasti mahal ya.
      *   Pipinya tembem banget (kepada bayi).
      *   Kirain Tulus (merujuk pada penyanyi Tulus).
      *   siap2 berubah jadi monster 🙌 (mengomentari @iben_ma yang terus berolahraga)
      
      Kesalahan prediksi juga sering terjadi pada kalimat-kalimat pendek (2-4 kata) yang jarang digunakan. Misalnya pada akun @samuelchrist, banyak yang memberi saran untuk kontennya dengan "Seberapa kaya (nama) bang"

2.   Tanggapan terhadap subjek/topik yang dibahas pada kontennya.

      @jeromepolin sering membahas soal matematika pada kontennya. Banyak yang berkomentar dengan kata "pusing" atau "ga ngerti", yang dilabeli negatif oleh model ini.

      @jennifervalda membuat konten tentang dirinya yang bersahabat hingga tidak masalah berbagi alat makan. Banyak komentar yang merasa *relate* dengan hal itu, tetapi banyak juga yang merasa jijik.

      @jennifervalda juga membuat konten yang menunjukkan momen ketika orang tua menujukkan video ke anaknya dan sang anak biasanya pura2 tertawa. Komentar seperti "padahal ga lucu", "ketawa nya dipaksa😭", dan "Sering sekali anjirr🤣"


3.   Komentar yang dimaksudkan untuk mentertawakan tingkah laku konten kreator.

      Pada akun @jeromepolin muncul komentar-komentar penggemar yang mentertawakan dirinya, misalnya seperti:
    
      *   Kenapa harus gitu muka nya jer 🤣.
      *   Pliss muka nya 🤣🤣
      *   Bang, ngga cocok bang 😂.

## Ujaran Minta-Minta | [Persentase](#persentase-komentar-positif-dan-negatif--ujaran-minta-minta--wordcloud) | [Wordcloud](#wordcloud--persentase--ujaran-minta-minta)
![Minta](https://github.com/user-attachments/assets/645d2ba6-5bf5-4bfc-a011-ec8c1aa34cb7)

Tingginya persentase ujaran minta-minta tentunya dipengaruhi oleh konten yang dibuat.

1.   Lebih dari 10%

      Mulai dari @willie27 hingga @adlinemargaret adalah akun-akun yang pernah membuat atau bahkan masih membuat konten membagi-bagikan uang, baik bertujuan untuk membantu, giveaway, atau dengan memberi tantangan tertentu.

2.   Lebih dari 5%

      @siscakohl memang dikenal memiliki uang yang banyak dari berbagai hal yang Ia lakukan di kontennya, tetapi Ia jarang membagikan uang ataupun barang secara langsung.

      @samuelchrist sempat mencoba membuat konten "Mengabulkan permintaan followers".

3.   Kurang dari 5%

      Keempat akun dengan persentase yang sangat kecil ini memang tidak pernah membuat konten membagi-bagikan barang ataupun uang.


## Wordcloud | [Persentase](#persentase-komentar-positif-dan-negatif--ujaran-minta-minta--wordcloud) | [Ujaran Minta-Minta](#ujaran-minta-minta--persentase--wordcloud)
<table>
  <tr>
    <th>@siscakohl</th>
    <th>@willie27_</th>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/sisca_2022.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/willie_2022.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/sisca_2023.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/willie_2023.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/sisca_2024.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/willie_2024.png" alt="Description" width="500"></td>
  </tr>
</table>

<table>
  <tr>
    <th>@riccienick</th>
    <th>@adeline</th>
  </tr>
  <tr>
    <td></td>
    <td><img src="wordcloud/wordcloud_results/adeline_2022.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/riccienick_2023.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/adeline_2023.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/riccienick_2024.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/adeline_2024.png" alt="Description" width="500"></td>
  </tr>
</table>

<table>
  <tr>
    <th>@fujian</th>
    <th>@jerome</th>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/fujian_2022.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/jerome_2022.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/fujian_2023.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/jerome_2023.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/fujian_2024.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/jerome_2024.png" alt="Description" width="500"></td>
  </tr>
</table>

<table>
  <tr>
    <th>@nasya</th>
    <th>@saaih</th>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/nasya_2022.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/saaih_2022.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/nasya_2023.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/saaih_2023.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/nasya_2024.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/saaih_2024.png" alt="Description" width="500"></td>
  </tr>
</table>

<table>
  <tr>
    <th>@ibenma</th>
    <th>@samuel</th>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/ibenma_2022.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/samuel_2022.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/ibenma_2023.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/samuel_2023.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/ibenma_2024.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/samuel_2024.png" alt="Description" width="500"></td>
  </tr>
</table>

<table>
  <tr>
    <th>@vilmei</th>
    <th>@deris</th>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/vilmei_2022.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/deris_2022.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/vilmei_2023.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/deris_2023.png" alt="Description" width="500"></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/vilmei_2024.png" alt="Description" width="500"></td>
    <td><img src="wordcloud/wordcloud_results/deris_2024.png" alt="Description" width="500"></td>
  </tr>
</table>

<table>
  <tr>
    <th>@jennifervalda</th>
    <th></th>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/jennifervalda_2022.png" alt="Description" width="500"></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/jennifervalda_2023.png" alt="Description" width="500"></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="wordcloud/wordcloud_results/jennifervalda_2024.png" alt="Description" width="500"></td>
    <td></td>
  </tr>
</table>

[Wordcloud](#wordcloud--persentase--ujaran-minta-minta) | [Persentase](#persentase-komentar-positif-dan-negatif--ujaran-minta-minta--wordcloud) | [Ujaran Minta-Minta](#ujaran-minta-minta--persentase--wordcloud)
