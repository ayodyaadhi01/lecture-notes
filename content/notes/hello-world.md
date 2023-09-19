---
title: "LSM Kasih Sayang Anak"
date: 2023-09-18T07:44:00+07:00
authors: ['Ayodya Adhi']
tags: ['21181017']
draft: false
math: true
url: "pedulianak"
---
{{< toc >}}

# purpose and objectives LSM
Peduli anak adalah inti dari misi kami di LSM ini. Kami memahami bahwa anak-anak adalah aset berharga masa depan. Melalui program-program pendidikan, kesejahteraan, dan perlindungan, kami berkomitmen untuk memberikan mereka peluang yang layak dan lingkungan yang aman untuk tumbuh dan berkembang. 
Kami tidak hanya menawarkan bantuan finansial, tetapi juga mendengarkan, memahami, dan mendukung kebutuhan anak-anak. Bersama dengan masyarakat, kami berusaha memerangi masalah seperti pengabaian dan pelecehan anak. Setiap tindakan kecil yang kita lakukan memiliki dampak besar pada masa depan mereka. Dengan bersatu, kita bisa menciptakan dunia yang lebih baik untuk generasi mendatang.

# Popularitas Warna dikalangan Anak
{{< chart 90 200 >}}
{
    type: 'bar',
    data: {
        labels: ['Red', 'Orange', 'Yellow', 'Green', 'Blue', 'Purple'],
        datasets: [{
            label: 'Terendah',
            data: [12, 19, 18, 16, 13, 14],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}

# animation with svg
{{< html >}}
<svg style="background: #eee;">
  <rect x="0" y="50" width="50" height="50">
    <animate
      attributeName="x"
      from="0" to="300"
      begin="0s" dur="2s"
      repeatCount="indefinite" />
  </rect>
</svg>
{{< /html >}}


# svg
{{< html >}}
<svg style="background: #ccc;" width="200" height="200">
  <rect x="40" y="25" width="100" height="60"
  style="
    fill: lightblue;">
  </rect>
  <rect x="70" y="45" width="100" height="60"
  style="
    fill: blue;
    fill-opacity: 0.2;">
  </rect>
  <rect x="120" y="65" width="100" height="60"
  style="
    fill: blue;
    fill-opacity: 0.5;">
  </rect>
</svg>
{{< /html >}}


{{< html >}}
<svg style="background: magenta;" width="200" height="200">
  <rect width="50" height="50"></rect>
  <rect x="100" y="20" width="50" height="50" fill="blue"></rect>
</svg>
{{< /html >}}


# diagram
{{< mermaid >}}
flowchart LR
  B --> I & P --> O & E
  B(("<b>Begin</b>"))
  I[/"Input"/]
  P["Process"]
  O[/"Output"/]
  E(("End"))
{{< /mermaid >}}


{{< mermaid >}}
flowchart LR
  B --> I --> P --> O --> E
  B(("Begin"))
  I[/"Input"/]
  P["Process"]
  O[/"Output"/]
  E(("End"))
{{< /mermaid >}}


# youtube
{{< youtube CEv8dgvKvc0 >}}


# image
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSwkZVEQYXZON_NijxLgbMBAPWQ4XHIhpZusYzwX1M2Uky2vJJw8VTB3pb0vI257b6BDik&usqp=CAU)


# table
No | Tanggal | Kegiatan | Info
:-: | :- | -: | :-:
1 | 22 Jun | Latihan | -
2 | 15 Jul | UTS | $\frac{x}{y}$
3 | 16 Aug | Praktikum | [Instagram](https://www.instagram.com/)
4 | 31 Aug | UAS | -
5 | 2 Sep  | Remedial | **nothing**




# link
+ [Google](https://www.google.com/)
+ [GitHub](https://github.com)


# list
+ Item
  - dua
  - tiga
+ item lain
+ item lain lagi


# equation
$$
\mathbf{M} = 
\left[
\begin{matrix}
1 & 2 & 3 & 4 & 5 \newline
1 & 2 & 3 & 4 & 5 \newline
1 & 2 & y^2 & z & x \newline
\end{matrix}
\right]
$$


$$
x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$


$$\tag{23}
y = ax^2 + bx + c
$$


# quote

> Ini adalah kutipan Ini adalah kutipan Ini adalah kutipanIni adalah kutipan Ini adalah kutipanIni adalah kutipan

# bold & italics

**bold** _italics_