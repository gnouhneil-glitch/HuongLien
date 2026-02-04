<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Quản Lý Điểm Lớp Học</title>
    <style>
        body { font-family: sans-serif; max-width: 1000px; margin: 2rem auto; }
        table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        th, td { border: 1px solid #ddd; padding: 10px; text-align: center; }
        th { background: #f4f4f4; }
        input { padding: 6px; width: 150px; }
        button { padding: 6px 10px; cursor: pointer; }
        .actions button { margin: 0 3px; }
    </style>
</head>
<body>

<h2>🏫 Quản Lý Điểm Lớp CNTT 2.K24</h2>

<!-- FORM -->
<h3>➕ Thêm / Sửa Học Sinh</h3>
<input type="hidden" id="editIndex">
<input id="name" placeholder="Họ tên">
<input id="math" type="number" placeholder="Toán">
<input id="phys" type="number" placeholder="Văn">
<input id="chem" type="number" placeholder="Anh">
<button onclick="saveStudent()">Lưu</button>

<table>
    <thead>
        <tr>
            <th>STT</th>
            <th>Họ Tên</th>
            <th>Toán</th>
            <th>Văn</th>
            <th>Anh</th>
            <th>Trung Bình</th>
            <th>Hành Động</th>
        </tr>
    </thead>
    <tbody id="tableBody"></tbody>
</table>

<script>
let students = [
    { name: "Nguyễn Văn An", math: 7, phys: 6, chem: 8 },
    { name: "Trần Hương Liên", math: 10, phys: 9, chem: 9 },
    { name: "Vũ Trọng Đức", math: 9, phys: 8, chem: 8 },
];

// HIỂN THỊ
function renderTable() {
    const tableBody = document.getElementById("tableBody");
    tableBody.innerHTML = "";

    students.forEach((s, index) => {
        const avg = ((s.math + s.phys + s.chem) / 3).toFixed(1);
        tableBody.innerHTML += `
            <tr>
                <td>${index + 1}</td>
                <td>${s.name}</td>
                <td>${s.math}</td>
                <td>${s.phys}</td>
                <td>${s.chem}</td>
                <td style="color:${avg >= 5 ? 'green' : 'red'}"><b>${avg}</b></td>
                <td class="actions">
                    <button onclick="editStudent(${index})">✏️</button>
                    <button onclick="deleteStudent(${index})">🗑️</button>
                </td>
            </tr>
        `;
    });
}

// LƯU (THÊM / SỬA)
function saveStudent() {
    const name = document.getElementById("name").value;
    const math = Number(document.getElementById("math").value);
    const phys = Number(document.getElementById("phys").value);
    const chem = Number(document.getElementById("chem").value);
    const editIndex = document.getElementById("editIndex").value;

    if (!name) {
        alert("Vui lòng nhập họ tên!");
        return;
    }

    const student = { name, math, phys, chem };

    if (editIndex === "") {
        students.push(student); // THÊM
    } else {
        students[editIndex] = student; // SỬA
        document.getElementById("editIndex").value = "";
    }

    clearForm();
    renderTable();
}

// SỬA
function editStudent(index) {
    const s = students[index];
    document.getElementById("name").value = s.name;
    document.getElementById("math").value = s.math;
    document.getElementById("phys").value = s.phys;
    document.getElementById("chem").value = s.chem;
    document.getElementById("editIndex").value = index;
}

// XÓA
function deleteStudent(index) {
    if (confirm("Bạn có chắc muốn xóa?")) {
        students.splice(index, 1);
        renderTable();
    }
}

// RESET FORM
function clearForm() {
    document.getElementById("name").value = "";
    document.getElementById("math").value = "";
    document.getElementById("phys").value = "";
    document.getElementById("chem").value = "";
}

renderTable();
</script>

</body>
</html>
