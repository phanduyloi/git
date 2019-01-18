# git
Git là một hệ thống quản lý phiên bản phân tán, có khả năng tách nhánh( branch), hỗ trợ rất tốt cho teamwork vì khả năng phân chia task, tổng hợp code trở nên dễ dàng hơn.
# mục đích
Lợi ích lớn nhất khi dùng Git:
    - Sắp xếp công việc tốt hơn.
    - Linh hoạt hơn khi phải làm cùng lúc nhiều task.
    - Tự tin hơn khi thử nghiệm những ý tưởng mới.
# mô hình git
  - Git structures: workspace, staging Area, local repository.
  - Remote repository.
# cấu trúc git client :Git structures
Staging Area là khu vực lưu trữ trung gian, lưu trữ những thay đổi trên tập tin để có thể commit.Là tạo thư mục và ko làm gì
Workspace là nơi làm việc. Sử dụng lệnh git add thêm file lên Workspace chuân bị cho commit
Local repository là kho lưu trữ trên máy. Khi thực hiện lệnh commmit
# Remote repository
    -Là nơi để lưu local repository trên internet, nhưng chỉ lưu những dữ liệu được push lên.
    -Mục đích: dễ dàng lấy về sử dụng bất cứ lúc nào, bất cứ ở đâu, share cho người khác sử dụng.
    -Có thể là một dịch vụ máy chủ Repository bất kỳ như: Github, Bitbucket, Backlog,...
