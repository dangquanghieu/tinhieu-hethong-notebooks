# Thuật ngữ Việt – Anh

> Bảng thuật ngữ dùng thống nhất trong giáo trình và các notebook của học phần. Khi soạn notebook (kể cả bằng Copilot), luôn dùng dạng ở cột **Thuật ngữ** và tuân theo mục **Chính tả**.

## Thuật ngữ chuyên môn

| Thuật ngữ | Tiếng Anh | Lưu ý |
|---|---|---|
| biến đổi $z$ | z-transform |  |
| biến đổi $z$ một phía | unilateral (one-sided) z-transform |  |
| biến đổi $z$ ngược | inverse z-transform |  |
| biến đổi Laplace | Laplace transform |  |
| biến đổi Laplace một phía | unilateral (one-sided) Laplace transform |  |
| biến đổi Laplace ngược | inverse Laplace transform |  |
| miền hội tụ (ROC) | region of convergence |  |
| điểm cực | pole |  |
| điểm không | zero |  |
| cực bội bậc $m$ | pole of multiplicity $m$ |  |
| hàm truyền | transfer function | Không dùng "hàm truyền đạt" |
| đáp ứng xung | impulse response |  |
| đáp ứng tần số | frequency response |  |
| phương trình sai phân tuyến tính hệ số hằng | linear constant-coefficient difference equation (LCCDE) |  |
| hàm xung đơn vị | unit impulse |  |
| hàm nhảy đơn vị | unit step | Không dùng "hàm nhảy bậc đơn vị" |
| dãy xung chữ nhật | rectangular sequence |  |
| dãy nhân quả | causal sequence |  |
| dãy phản nhân quả | anti-causal sequence |  |
| dãy phía phải / phía trái / hai phía | right-sided / left-sided / two-sided sequence |  |
| vòng tròn đơn vị | unit circle |  |
| khai triển thành các phân thức tối giản | partial fraction expansion |  |
| khai triển thành chuỗi lũy thừa | power series expansion |  |
| tính chất tuyến tính | linearity |  |
| dịch thời gian | time shifting | Cùng nghĩa "phép dịch" |
| co dãn trên miền $z$ | scaling in the z-domain |  |
| đảo trục thời gian | time reversal | Cùng nghĩa "phép lấy đối xứng" |
| liên hợp phức | complex conjugation |  |
| tính chất chập | convolution property |  |
| đạo hàm trên miền $z$ | differentiation in the z-domain |  |
| định lý giá trị đầu / cuối | initial / final value theorem |  |
| điều kiện đầu | initial conditions |  |
| hệ thống ổn định (BIBO) | BIBO stable system |  |
| hệ thống cực–không | pole-zero system |  |
| hệ toàn cực | all-pole system | Không dùng "IIR gồm toàn điểm cực" |
| hệ thống FIR / IIR | FIR / IIR system (finite / infinite impulse response) | Phân loại theo chiều dài của $h[n]$ |
| sơ đồ dạng trực tiếp I / II | direct form I / II |  |
| phần tử trễ | delay element |  |
| bộ cộng | adder |  |
| tiêu chuẩn Jury, Schur–Cohn | Jury / Schur–Cohn stability test |  |
| phép chập; tổng chập; tích phân chập | convolution; convolution sum; convolution integral | Không dùng "tích chập" |
| độ phức tạp tính toán (của phép chập) | computational complexity |  |
| đáp ứng nhảy | step response |  |
| giá trị xác lập; thời gian xác lập | steady-state value; settling time |  |
| điều kiện nghỉ ban đầu | initial rest |  |
| hệ thống không có nhớ | memoryless system |  |
| hệ thống khả nghịch; hệ thống nghịch đảo | invertible system; inverse system |  |
| phương trình đặc trưng; nghiệm thuần nhất; nghiệm riêng | characteristic equation; homogeneous solution; particular solution |  |
| cộng hưởng | resonance |  |
| dạng chính tắc | canonic form |  |
| tương quan chéo; tự tương quan | cross-correlation; autocorrelation |  |
| chứng minh phản đảo | proof by contrapositive |  |
| tín hiệu một chiều / nhiều chiều | one-dimensional / multi-dimensional signal |  |
| tín hiệu một kênh / nhiều kênh | one-channel / multi-channel signal |  |
| tín hiệu xác định / ngẫu nhiên | deterministic / random signal |  |
| tín hiệu liên tục / rời rạc theo thời gian | continuous-time / discrete-time signal |  |
| tín hiệu năng lượng; tín hiệu công suất | energy signal; power signal |  |
| công suất tức thời; công suất trung bình | instantaneous power; average power |  |
| phép dịch; phép co dãn; phép lấy đối xứng | time shifting; scaling; reflection (folding, time reversal) | "phép dịch" = "dịch thời gian"; "phép lấy đối xứng" = "đảo trục thời gian" |
| tín hiệu tuần hoàn; chu kỳ cơ bản | periodic signal; fundamental period |  |
| tín hiệu chẵn (đối xứng) / lẻ (phản đối xứng) | even / odd signal |  |
| hàm dốc đơn vị | unit ramp |  |
| hàm delta Dirac | Dirac delta function | = hàm xung đơn vị liên tục $\delta(t)$ |
| hàm suy rộng | generalized function |  |
| tính chất lấy mẫu (của hàm xung đơn vị) | sampling (sifting) property |  |
| kênh đa đường | multipath channel |  |
| mô hình kênh (tạo mô hình kênh) | channel modeling |  |
| ước lượng kênh | channel estimation |  |
| điều chế biên độ | amplitude modulation (AM); DSB-SC |  |
| kích thích; đáp ứng | excitation; response |  |
| hệ thống nhân quả | causal system |  |
| hệ thống bất biến / thay đổi theo thời gian | time-invariant / time-varying system |  |
| hệ thống tuyến tính / phi tuyến | linear / nonlinear system |  |
| ghép nối tiếp / song song / hồi tiếp | series (cascade) / parallel / feedback interconnection |  |
| chuỗi Fourier (FS); chuỗi Fourier cho tín hiệu rời rạc (DTFS) | Fourier series; discrete-time Fourier series |  |
| hệ số chuỗi Fourier; hệ số phổ | Fourier series coefficients; spectral coefficients |  |
| thành phần hài bậc $k$; tần số cơ bản | $k$-th harmonic; fundamental frequency |  |
| điều kiện Dirichlet | Dirichlet conditions |  |
| biến đổi Fourier (FT); biến đổi Fourier của tín hiệu rời rạc | Fourier transform; discrete-time Fourier transform (DTFT) | Sách ký hiệu cả hai là FT |
| biến đổi Fourier mở rộng | generalized Fourier transform | Cho tín hiệu tuần hoàn, hình sin |
| phổ; phổ biên độ; phổ pha; phổ vạch | spectrum; magnitude spectrum; phase spectrum; line spectrum |  |
| đối ngẫu (tính chất) | duality |  |
| quan hệ Parseval; định lý Plancherel | Parseval's relation; Plancherel theorem |  |
| khả tích tuyệt đối; khả tổng tuyệt đối | absolutely integrable; absolutely summable |  |
| hàm sinc; búp chính; búp phụ | sinc function; main lobe; side lobe |  |
| tín hiệu băng cơ sở; tín hiệu thông dải | baseband signal; bandpass signal |  |
| đáp ứng biên độ; đáp ứng pha; pha tuyến tính | magnitude response; phase response; linear phase |  |
| bộ lọc chọn lọc tần số | frequency-selective filter |  |
| bộ lọc thông thấp / thông cao / thông dải / chắn dải | lowpass / highpass / bandpass / bandstop filter |  |
| dải thông; dải chắn; dải chuyển tiếp | passband; stopband; transition band |  |
| độ gợn sóng dải thông / dải chắn | passband / stopband ripple |  |
| tần số cắt | cutoff frequency |  |
| tần số gãy | corner frequency (break frequency) |  |
| đường tiệm cận | asymptote |  |
| tần số góc tự nhiên | natural frequency | $\Omega_n$ |
| hệ số tắt dần | damping ratio | $\zeta$ |
| tần số cộng hưởng; đỉnh cộng hưởng | resonant frequency; resonant peak | $\Omega_r$, $M_p$ |
| hệ thống pha tối thiểu | minimum-phase system |  |
| băng thông; băng thông 3-dB | bandwidth; 3-dB bandwidth | Không dùng "độ rộng dải thông". Băng thông là độ rộng (một số); dải thông là một khoảng tần số |
| biểu đồ Bode | Bode plot | Không dùng "đồ thị Bode" |
| bộ lọc thích nghi | adaptive filter |  |
| phổ mật độ năng lượng; phổ mật độ công suất | energy spectral density; power spectral density | Năng lượng: tín hiệu xác định; công suất: tín hiệu ngẫu nhiên dừng |
| định lý Wiener–Khintchine | Wiener–Khinchin theorem |  |
| dừng theo nghĩa rộng | wide-sense stationary (WSS) |  |
| chồng phổ | aliasing |  |
| lấy mẫu; chu kỳ lấy mẫu; tần số lấy mẫu | sampling; sampling period; sampling frequency (sampling rate) |  |
| chuẩn hóa (sau lấy mẫu) | normalization |  |
| định lý lấy mẫu | sampling theorem |  |
| tốc độ Nyquist | Nyquist rate | $= 2B$, ngưỡng dưới của $f_s$; phân biệt với tần số Nyquist |
| tần số Nyquist | Nyquist frequency | $= f_s/2$ |
| lấy mẫu bằng dãy xung đơn vị; dãy xung đơn vị tuần hoàn | impulse-train sampling; periodic impulse train |  |
| tín hiệu sau lấy mẫu | sampled signal | $x_s(t)$ |
| bản sao phổ | spectral replica | Không dùng "khối phổ" |
| khôi phục tín hiệu | signal reconstruction |  |
| tín hiệu tương tự | analog signal | = tín hiệu liên tục theo thời gian |
| bộ chuyển đổi tương tự – số (ADC) | analog-to-digital converter | Sách viết "bộ ADC" |
| hệ thống thông tin | communication system | Không dùng làm thuật ngữ chính: "hệ thống truyền tin", "hệ thống truyền thông" |
| máy phát; máy thu | transmitter (TX); receiver (RX) |  |
| kênh (thông tin); nhiễu cộng | channel; additive noise |  |
| tỷ số tín hiệu trên nhiễu | signal-to-noise ratio (SNR) | Viết "tỷ số" |
| điều chế; giải điều chế | modulation; demodulation |  |
| sóng mang | carrier |  |
| điều biên; điều tần; điều pha | amplitude modulation (AM); frequency modulation (FM); phase modulation (PM) |  |
| điều biên hai biên, triệt sóng mang | double-sideband suppressed-carrier (DSB-SC) | Sách viết "điều biên DSB-SC" |
| đường bao | envelope |  |
| trộn tần; nâng tần; hạ tần | mixing; upconversion (upconverter); downconversion (downconverter) |  |
| giải điều biên đồng bộ pha | coherent detection |  |
| vòng khóa pha | phase-locked loop (PLL) | Sách chỉ viết "PLL" |
| QAM | quadrature amplitude modulation |  |
| thành phần đồng pha / vuông pha (I/Q) | in-phase / quadrature |  |
| thông điệp | message |  |
| dạng sóng (tín hiệu điều chế) | waveform |  |
| nhiễu trắng Gauss | white Gaussian noise | Mật độ phổ công suất hai phía $N_0/2$ |
| mật độ phổ công suất (hai phía) | (two-sided) power spectral density |  |
| kỳ vọng | expectation (expected value) | $\mathbb{E}[\cdot]$ |
| phân phối chuẩn (Gauss) | normal (Gaussian) distribution | $\mathcal{N}(\mu, \sigma^2)$ |
| độc lập và cùng phân phối | independent and identically distributed (i.i.d.) |  |
| xác suất tiên nghiệm; xác suất hậu nghiệm | prior probability; posterior probability |  |
| bộ quyết định MAP; bộ quyết định ML | maximum a posteriori (MAP); maximum likelihood (ML) decision rule |  |
| xác suất lỗi; xác suất lỗi ký hiệu; tỷ lệ lỗi bit | probability of error P_e; symbol error probability P_s; bit error rate (BER) |  |
| không gian tín hiệu | signal space |  |
| không gian Hilbert; tích trong; chuẩn | Hilbert space; inner product; norm |  |
| hệ cơ sở trực chuẩn; thủ tục Gram–Schmidt | orthonormal basis; Gram–Schmidt procedure |  |
| định lý không liên quan | theorem of irrelevance |  |
| chòm sao tín hiệu; ký hiệu | signal constellation; symbol |  |
| truyền tín hiệu M-mức | M-ary signaling |  |
| PAM; PSK; BPSK; QPSK | pulse amplitude modulation; phase-shift keying; binary / quadrature PSK |  |
| OFDM | orthogonal frequency-division multiplexing |  |
| bộ tương quan; máy thu tương quan | correlator; correlation receiver |  |
| máy thu tối ưu | optimum receiver |  |
| khoảng cách Euclid; khoảng cách nhỏ nhất | Euclidean distance; minimum distance |  |
| mã Gray | Gray code |  |
| xung định dạng | pulse shaping (shaping pulse) | Không dùng "xung tạo dạng" |
| xung cos nâng | raised-cosine pulse |  |
| nhiễu liên ký hiệu (ISI) | intersymbol interference | Sách chỉ viết "ISI" |
| điều kiện Nyquist (ISI bằng không) | Nyquist criterion (for zero ISI) |  |
| hiệu suất phổ | spectral efficiency |  |
| bộ lọc phối hợp | matched filter (MF) | Không dùng "bộ lọc thích ứng" (tránh nhầm với bộ lọc thích nghi) |

## Chính tả

| Dùng | Không dùng |
|---|---|
| hữu tỷ | hữu tỉ |
| tọa độ, tùy, hòa (dấu kiểu mới) | toạ độ, tuỳ, hoà |
| quy đồng, quy ước | qui đồng, qui ước |
| lý tưởng | lí tưởng |

## Thuật ngữ bổ sung dùng trong notebook (chưa có trong giáo trình)

| Thuật ngữ | Tiếng Anh |
|---|---|
| trung bình trượt; bộ lọc trung bình trượt | moving average (filter) |
| quá độ (đoạn quá độ) | transient |
| tính giao hoán (của phép chập) | commutativity |
| xung vuông | rectangular pulse |
| quy tắc hình thang | trapezoidal rule |
| thử nghiệm Monte Carlo | Monte Carlo experiment |

## Ký hiệu dùng trong notebook

| Đại lượng | Ký hiệu | Đơn vị |
|---|---|---|
| chỉ số thời gian rời rạc | $n$ | mẫu |
| thời gian liên tục | $t$ | s |
| tần số rời rạc | $\omega$ | rad/mẫu |
| tần số góc liên tục | $\Omega$ | rad/s |
| tần số | $f$ | Hz |
| tần số lấy mẫu; chu kỳ lấy mẫu | $f_s$; $T_s$ | Hz; s |
| chỉ số DFT | $k$ | — |
