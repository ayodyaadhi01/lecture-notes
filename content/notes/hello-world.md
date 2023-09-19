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

## purpose and objectives LSM
Peduli anak adalah inti dari misi kami di LSM ini. Kami memahami bahwa anak-anak adalah aset berharga masa depan. Melalui program-program pendidikan, kesejahteraan, dan perlindungan, kami berkomitmen untuk memberikan mereka peluang yang layak dan lingkungan yang aman untuk tumbuh dan berkembang. 
Kami tidak hanya menawarkan bantuan finansial, tetapi juga mendengarkan, memahami, dan mendukung kebutuhan anak-anak. Bersama dengan masyarakat, kami berusaha memerangi masalah seperti pengabaian dan pelecehan anak. Setiap tindakan kecil yang kita lakukan memiliki dampak besar pada masa depan mereka. Dengan bersatu, kita bisa menciptakan dunia yang lebih baik untuk generasi mendatang.

## Minat Baca dikalangan Anak Berdasarkan Usia
{{< chart 90 200 >}}
{
    type: 'bar',
    data: {
        labels: ['0-3 Tahun', '4-6 Tahun', '7-9 Tahun', '10-15 Tahun', '16-20 Tahun', '20-15 Tahun'],
        datasets: [{
            label: 'Usia 0-3 Tahun memiliki minat baca yang rendah',
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
![]
(https://www.istockphoto.com/id/foto/anak-dalam-kemiskinan-gm147693608-8198095)


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

# Animation with SVG
{{< html >}}
<svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with animation -->
  <rect x="10" y="10" width="50" height="50" fill="blue">
    <animate attributeName="width" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="height" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="fill" values="blue;red;green;blue" dur="4s" begin="0s" repeatCount="indefinite" />
  </rect>
</svg>
{{< /html >}}

# Complex SVG with Styled Rect
{{< html >}}
<svg width="400" height="300" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with gradients -->
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgb(255,0,0);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgb(0,0,255);stop-opacity:1" />
    </linearGradient>
  </defs>

  <rect x="20" y="20" width="200" height="100" fill="url(#grad1)" stroke="green" stroke-width="3" />

  <!-- Text element -->
  <text x="30" y="160" font-family="Arial" font-size="24" fill="black">Complex SVG</text>

  <!-- Circle with animation -->
  <circle cx="250" cy="150" r="20" fill="orange">
    <animate attributeName="r" from="20" to="50" dur="2s" begin="0s" repeatCount="indefinite" />
  </circle>
</svg>
{{< /html >}}


## chart
{{< chart 90 200 >}}
{
    type: 'bar',
    data: {
        labels: ['2017', '2018', '2019', '2020', '2021', '2022'],
        datasets: [{
            label: 'Bar Chart',
            data: [12, 19, 18, 14, 20, 11],
            backgroundColor: [
                'rgba(255,99,132,0.2)',
                'rgba(54,162,235,0.2)',
                'rgba(255,206,86,0.2)',
                'rgba(75,192,192,0.2)',
                'rgba(153,102,255,0.2)',
                'rgba(255,159,64,0.2)'
            ],
            borderColor: [
                'rgba(255,99,132,1)',
                'rgba(54,162,235,1)',
                'rgba(255,206,86,1)',
                'rgba(75,192,192,1)',
                'rgba(153,102,255,1)',
                'rgba(255,159,64,1)'
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

## mermaid
{{< mermaid >}}
flowchart LR
    B --> I --> P --> O --> E
    B(("Variabilitas Tahun ke Tahun"))
    I(("Peningkatan Pemahaman"))
    P(("Perubahan Metode Ajar"))
    O(("Perubahan Faktor Sosbud"))
    E(("Program Pendidikan Tambahan"))
{{< /mermaid >}}

## chart
{{< chart 90 200 >}}
{
    type: 'bar',
    data: {
        labels: ['2018', '2019', '2020', '2021', '2022', '2023'],
        datasets: [{
            label: 'Bar Chart',
            data: [150, 150, 250, 300, 300, 300],
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