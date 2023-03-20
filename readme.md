# Multi-Channel Speech Enhancement results

This repo shows enhanced speech of TriU-Net and other models.

## Real recordings

SNR: -5 dB

Spk 1 is a 24-year-old male, while spk 2 is a 24-year-old female. Both spk 1 and spk 2 speek in Mandarin. 

<table>
  <tbody>
    <tr>
        <th>Signals </th>
        <th>Spk 1 babble</th>
        <th>Spk 2 babble</th>
        <th>Spk 1 f16</th>
        <th>Spk 2 f16</th>
    </tr>
    <tr>
      <td>noise</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/9ULA_synth_kkl_babble_snr-5.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/babble/9ULA_synth_kkl_babble_snr-5.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/9ULA_synth_yzh_babble_snr-5.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/babble/9ULA_synth_yzh_babble_snr-5.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/9ULA_synth_kkl_babble_snr-5.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/f16/9ULA_synth_kkl_f16_snr-5.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/9ULA_synth_yzh_f16_snr-5.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/f16/9ULA_synth_yzh_f16_snr-5.wav" controls></td>
    </tr>
    <tr>
      <td>clean</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/9ULA_kkl_clean.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/babble/9ULA_kkl_clean.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/9ULA_yzh_clean.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/babble/9ULA_yzh_clean.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/9ULA_kkl_clean.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/f16/9ULA_kkl_clean.wav" controls></td>      
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/9ULA_yzh_clean.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/f16/9ULA_yzh_clean.wav" controls></td>
    </tr>
    <tr>
      <td>oracl MB-MVDR</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_oracle_MBMVDR_kkl_babble_snr-5_pesq1.09_1.36.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/babble/real_enh_oracle_MBMVDR_kkl_babble_snr-5_pesq1.09_1.36.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_oracle_MBMVDR_yzh_babble_snr-5_pesq1.06_1.27.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/babble/real_enh_oracle_MBMVDR_yzh_babble_snr-5_pesq1.06_1.27.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_oracle_MBMVDR_kkl_f16_snr-5_pesq1.06_1.3.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/f16/real_enh_oracle_MBMVDR_kkl_f16_snr-5_pesq1.06_1.3.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_oracle_MBMVDR_yzh_f16_snr-5_pesq1.04_1.25.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/f16/real_enh_oracle_MBMVDR_yzh_f16_snr-5_pesq1.04_1.25.wav" controls></td>
    </tr>
    <tr>
      <td>EaBNet</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_EaBNet_kkl_babble_snr-5_pesq1.09_1.27.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/babble/real_enh_EaBNet_kkl_babble_snr-5_pesq1.09_1.27.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_EaBNet_yzh_babble_snr-5_pesq1.06_1.33.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/babble/real_enh_EaBNet_yzh_babble_snr-5_pesq1.06_1.33.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_EaBNet_kkl_f16_snr-5_pesq1.06_1.37.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/f16/real_enh_EaBNet_kkl_f16_snr-5_pesq1.06_1.37.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_EaBNet_yzh_f16_snr-5_pesq1.04_1.41.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/f16/real_enh_EaBNet_yzh_f16_snr-5_pesq1.04_1.41.wav" controls></td>
    </tr>
    <tr>
      <td>FaSNet</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_FaSNet_kkl_babble_snr-5_pesq1.09_1.24.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/babble/real_enh_FaSNet_kkl_babble_snr-5_pesq1.09_1.24.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_FaSNet_yzh_babble_snr-5_pesq1.06_1.23.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/babble/real_enh_FaSNet_yzh_babble_snr-5_pesq1.06_1.23.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_FaSNet_kkl_f16_snr-5_pesq1.06_1.35.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/f16/real_enh_FaSNet_kkl_f16_snr-5_pesq1.06_1.35.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_FaSNet_yzh_f16_snr-5_pesq1.04_1.47.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/f16/real_enh_FaSNet_yzh_f16_snr-5_pesq1.04_1.47.wav" controls></td>
    </tr>
    <tr>
      <td>Model A</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_ModelA_kkl_babble_snr-5_pesq1.09_1.42.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/babble/real_enh_ModelA_kkl_babble_snr-5_pesq1.09_1.42.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_ModelA_yzh_babble_snr-5_pesq1.06_1.26.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/babble/real_enh_ModelA_yzh_babble_snr-5_pesq1.06_1.26.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_ModelA_kkl_f16_snr-5_pesq1.06_1.6.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/f16/real_enh_ModelA_kkl_f16_snr-5_pesq1.06_1.6.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_ModelA_yzh_f16_snr-5_pesq1.04_1.77.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/f16/real_enh_ModelA_yzh_f16_snr-5_pesq1.04_1.77.wav" controls></td>
    </tr>
    <tr>
        <td><b>TriU-Net</b></td>
        <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_TriU-Net_kkl_babble_snr-5_pesq1.09_1.7.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/babble/real_enh_TriU-Net_kkl_babble_snr-5_pesq1.09_1.7.wav" controls></td>
        <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_TriU-Net_yzh_babble_snr-5_pesq1.06_1.65.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/babble/real_enh_TriU-Net_yzh_babble_snr-5_pesq1.06_1.65.wav" controls></td>
        <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_TriU-Net_kkl_f16_snr-5_pesq1.06_1.84.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk1/f16/real_enh_TriU-Net_kkl_f16_snr-5_pesq1.06_1.84.wav" controls></td>
        <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/real_enh_TriU-Net_yzh_f16_snr-5_pesq1.04_1.9.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/real%20recording/spk2/f16/real_enh_TriU-Net_yzh_f16_snr-5_pesq1.04_1.9.wav" controls></td>
    </tr>
  </tbody>
  <colgroup>
    <col style="width: 5%;">
    <col style="width: 5%;">
    <col style="width: 5%;">
    <col style="width: 5%;">
  </colgroup>
</table>






## Synthetic Data

<table>
  <tbody>
    <tr>
        <th>Signals </th>
        <th>Spk 1 SNR:-5.36 dB</th>
        <th>Spk 2 SNR:-3.43 dB</th>
    </tr>
    <tr>
      <td>noise</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/1_sir-5.36dB_noisyR0.95_noisy.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk1/1_sir-5.36dB_noisyR0.95_noisy.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/4_sir-3.43dB_noisyR0.67_noisy.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk2/4_sir-3.43dB_noisyR0.67_noisy.wav" controls></td>
    </tr>
    <tr>
      <td>clean</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/1_sir-5.36dB_noisyR0.95_clean.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk1/1_sir-5.36dB_noisyR0.95_clean.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/4_sir-3.43dB_noisyR0.67_clean.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk2/4_sir-3.43dB_noisyR0.67_clean.wav" controls></td>
    </tr>
    <tr>
      <td>EaBNet</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/1_sir-5.36dB_noisyR0.95_EaBNet.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk1/1_sir-5.36dB_noisyR0.95_EaBNet.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/4_sir-3.43dB_noisyR0.67_EaBNet.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk2/4_sir-3.43dB_noisyR0.67_EaBNet.wav" controls></td>
    </tr>
    <tr>
      <td>FaSNet</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/1_sir-5.36dB_noisyR0.95_FaSNet.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk1/1_sir-5.36dB_noisyR0.95_FaSNet.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/4_sir-3.43dB_noisyR0.67_FaSNet.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk2/4_sir-3.43dB_noisyR0.67_FaSNet.wav" controls></td>
    </tr>
    <tr>
      <td>Model A</td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/1_sir-5.36dB_noisyR0.95_ModelA.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk1/1_sir-5.36dB_noisyR0.95_ModelA.wav" controls></td>
      <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/4_sir-3.43dB_noisyR0.67_ModelA.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk2/4_sir-3.43dB_noisyR0.67_ModelA.wav" controls></td>
    </tr>
    <tr>
        <td><b>TriU-Net</b></td>
        <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/1_sir-5.36dB_noisyR0.95_TriU-Net.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk1/1_sir-5.36dB_noisyR0.95_TriU-Net.wav" controls></td>
        <td><img src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/spectrograms/4_sir-3.43dB_noisyR0.67_TriU-Net.jpg"><audio src="https://raw.githubusercontent.com/CaA23187/TriU-Net_demo/main/test%20set/spk2/4_sir-3.43dB_noisyR0.67_TriU-Net.wav" controls></td>
    </tr>
  </tbody>
  <colgroup>
    <col style="width: 5%;">
    <col style="width: 5%;">
    <col style="width: 5%;">
    <col style="width: 5%;">
  </colgroup>
</table>










## Other samples

Other SNR scenarios  See https://github.com/CaA23187/TriU-Net_demo

 



